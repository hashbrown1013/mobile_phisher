<div id="maincontent">
<div id="outputFigDisplay" class="fig-ansi">
<pre id="taag_output_text" class="fig-ansi" contenteditable="true">███╗   ███╗ ██████╗ ██████╗ ██╗██╗     ███████╗        ██████╗ ██╗  ██╗██╗███████╗██╗  ██╗███████╗██████╗ 
████╗ ████║██╔═══██╗██╔══██╗██║██║     ██╔════╝        ██╔══██╗██║  ██║██║██╔════╝██║  ██║██╔════╝██╔══██╗
██╔████╔██║██║   ██║██████╔╝██║██║     █████╗          ██████╔╝███████║██║███████╗███████║█████╗  ██████╔╝
██║╚██╔╝██║██║   ██║██╔══██╗██║██║     ██╔══╝          ██╔═══╝ ██╔══██║██║╚════██║██╔══██║██╔══╝  ██╔══██╗
██║ ╚═╝ ██║╚██████╔╝██████╔╝██║███████╗███████╗███████╗██║     ██║  ██║██║███████║██║  ██║███████╗██║  ██║
╚═╝     ╚═╝ ╚═════╝ ╚═════╝ ╚═╝╚══════╝╚══════╝╚══════╝╚═╝     ╚═╝  ╚═╝╚═╝╚══════╝╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝
                                                                                                          </pre>
<div>&nbsp;</div>
</div>
</div>
<h1 align="center">Mobile_Phisher</h1> <p align="center">Get Credentials on Your Email instead of Getting Blocked by Free Hosting Websites</p>
Mobile_phisher allows you to host mobile Phishing Pages on 000webhost.com without Getting your Account deleted

<div id="maincontent">
<div id="outputFigDisplay" class="fig-ansi">
<pre id="taag_output_text" class="fig-ansi" contenteditable="true">██╗    ██╗██╗  ██╗██╗   ██╗    ████████╗██╗  ██╗██╗███████╗    ████████╗ ██████╗  ██████╗ ██╗     
██║    ██║██║  ██║╚██╗ ██╔╝    ╚══██╔══╝██║  ██║██║██╔════╝    ╚══██╔══╝██╔═══██╗██╔═══██╗██║     
██║ █╗ ██║███████║ ╚████╔╝        ██║   ███████║██║███████╗       ██║   ██║   ██║██║   ██║██║     
██║███╗██║██╔══██║  ╚██╔╝         ██║   ██╔══██║██║╚════██║       ██║   ██║   ██║██║   ██║██║     
╚███╔███╔╝██║  ██║   ██║          ██║   ██║  ██║██║███████║       ██║   ╚██████╔╝╚██████╔╝███████╗
 ╚══╝╚══╝ ╚═╝  ╚═╝   ╚═╝          ╚═╝   ╚═╝  ╚═╝╚═╝╚══════╝       ╚═╝    ╚═════╝  ╚═════╝ ╚══════╝
                                                                                                  </pre>
<div>&nbsp;</div>
</div>
</div>

000webhost.com Blocks Those Guys Who Uploads a Nice looking index.html file that calls a stupid looking php file which saves a text file in the website, and that text file contains all passwords that were captured by your nice looking index.html, But This On The Other Hand Does Something Else. it Sends Captured Passwords to Attacker's Email.

# How Does This Saves Us From Getting Blocked?
In this case we upload a nice looking index.html and a stupid looking php, But the Diffrence is that this php does not saves the Credentials in a text file but instead sends them to the attacker via email.

<div id="maincontent">
<div id="outputFigDisplay" class="fig-ansi">
<pre id="taag_output_text" class="fig-ansi" contenteditable="true">███████╗███████╗████████╗██╗   ██╗██████╗ 
██╔════╝██╔════╝╚══██╔══╝██║   ██║██╔══██╗
███████╗█████╗     ██║   ██║   ██║██████╔╝
╚════██║██╔══╝     ██║   ██║   ██║██╔═══╝ 
███████║███████╗   ██║   ╚██████╔╝██║     
╚══════╝╚══════╝   ╚═╝    ╚═════╝ ╚═╝     
                                          </pre>
<div>&nbsp;</div>
</div>
</div>

[1] create a free account on 000webhost.com

[2] login to file manager

[3] create a folder to keep your files

[4] upload all the three files in mobile_phisher to your folder that you created in step-3.

[5] edit action.php and add any valid email to line 14 ( without brackets )
The email that you add to line 14 is the email address that you will get your credential emails from ( it will br spoofed )

[6] add your email ( Receiver's Email ) to line 15.


[7] save and close action.php and go to your website

https://yoursubdomain.000webhostapp.com/yourfolder/index.html

<div id="maincontent">
<div id="outputFigDisplay" class="fig-ansi">
<pre id="taag_output_text" class="fig-ansi" contenteditable="true">███████╗ ██████╗██████╗ ███████╗███████╗███╗   ██╗███████╗██╗  ██╗ ██████╗ ████████╗███████╗
██╔════╝██╔════╝██╔══██╗██╔════╝██╔════╝████╗  ██║██╔════╝██║  ██║██╔═══██╗╚══██╔══╝██╔════╝
███████╗██║     ██████╔╝█████╗  █████╗  ██╔██╗ ██║███████╗███████║██║   ██║   ██║   ███████╗
╚════██║██║     ██╔══██╗██╔══╝  ██╔══╝  ██║╚██╗██║╚════██║██╔══██║██║   ██║   ██║   ╚════██║
███████║╚██████╗██║  ██║███████╗███████╗██║ ╚████║███████║██║  ██║╚██████╔╝   ██║   ███████║
╚══════╝ ╚═════╝╚═╝  ╚═╝╚══════╝╚══════╝╚═╝  ╚═══╝╚══════╝╚═╝  ╚═╝ ╚═════╝    ╚═╝   ╚══════╝
                                                                                            </pre>
<div>&nbsp;</div>
</div>
</div>
<h1 align="center">**********Website Preview**********</h1>

<p align="center">
  <img src="http://pwnedbyme.000webhostapp.com/preview.jpg">
</p>

<h1 align="center">**********Email Preview**********</h1>

<p align="center">
  <img src="http://pwnedbyme.000webhostapp.com/preview1.jpg">
</p>






<div id="maincontent">
<div id="outputFigDisplay" class="fig-ansi">
<pre id="taag_output_text" class="fig-ansi" contenteditable="true">            ██████╗ ██╗███████╗ ██████╗██╗      █████╗ ██╗███╗   ███╗███████╗██████╗ 
            ██╔══██╗██║██╔════╝██╔════╝██║     ██╔══██╗██║████╗ ████║██╔════╝██╔══██╗
            ██║  ██║██║███████╗██║     ██║     ███████║██║██╔████╔██║█████╗  ██████╔╝
            ██║  ██║██║╚════██║██║     ██║     ██╔══██║██║██║╚██╔╝██║██╔══╝  ██╔══██╗
            ██████╔╝██║███████║╚██████╗███████╗██║  ██║██║██║ ╚═╝ ██║███████╗██║  ██║
            ╚═════╝ ╚═╝╚══════╝ ╚═════╝╚══════╝╚═╝  ╚═╝╚═╝╚═╝     ╚═╝╚══════╝╚═╝  ╚═╝
                                                                                     </pre>
<div>&nbsp;</div>
</div>
</div>

<p align="center">
  TO BE USED FOR EDUCATIONAL PURPOSES ONLY
</p>


The use of the Mobile_Phisher is COMPLETE RESPONSIBILITY of the END-USER. Developers assume NO liability and are NOT responsible for any misuse or damage caused by this project.

<p align="center">
"DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE."
 </p>
