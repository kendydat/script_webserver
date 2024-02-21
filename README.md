<div _ngcontent-ng-c3190845649="" class="markdown markdown-main-panel ui-v2-enabled" dir="ltr" style="--animation-duration: 600ms; --fade-animation-function: cubic-bezier(0.05, 0.7, 0.91, 1);"><p data-sourcepos="3:1-3:85"><strong>Bash Script to Setup Nginx, PHP 7.4, Composer, Node.js, and PM2 on Amazon Linux 2</strong></p><p data-sourcepos="5:1-5:16"><strong>Description:</strong></p><p data-sourcepos="7:1-7:113">This script automates the setup of a web development environment on Amazon Linux 2 with the following components:</p><ul data-sourcepos="9:1-14:0">
<li data-sourcepos="9:1-9:23">Nginx as a web server</li>
<li data-sourcepos="10:1-10:35">PHP 7.4 as the scripting language</li>
<li data-sourcepos="11:1-11:36">Composer for dependency management</li>
<li data-sourcepos="12:1-12:36">Node.js for JavaScript development</li>
<li data-sourcepos="13:1-14:0">PM2 for process management</li>
</ul><p data-sourcepos="15:1-15:17"><strong>Requirements:</strong></p><ul data-sourcepos="17:1-20:0">
<li data-sourcepos="17:1-17:23">Amazon Linux 2 server</li>
<li data-sourcepos="18:1-18:21">Root or sudo access</li>
<li data-sourcepos="19:1-20:0">Git installed</li>
</ul><p data-sourcepos="21:1-21:10"><strong>Usage:</strong></p><ol data-sourcepos="23:1-24:0">
<li data-sourcepos="23:1-24:0">Clone the repository to your local machine:</li>
</ol><code-block _nghost-ng-c3863015178="" ng-version="0.0.0-PLACEHOLDER"><!----><div _ngcontent-ng-c3863015178="" class="code-block ng-star-inserted"><!----><pre _ngcontent-ng-c3863015178=""><code _ngcontent-ng-c3863015178="" role="text" data-test-id="code-content" class="code-container no-decoration-radius">git clone https://github.com/kendydat/script_webserver.git
</code></pre><!----><!----><!----><!----></div><!----></code-block><ol data-sourcepos="29:1-34:0" start="2">
<li data-sourcepos="29:1-30:0">
<p data-sourcepos="29:4-29:87">Upload the <code>server-amazon-linux2-nginx-php74.sh</code> file to your Amazon Linux 2 server.(or download <code-block>curl -o server-amazon-linux2-nginx-php74.sh https://raw.githubusercontent.com/kendydat/script_webserver/main/server-amazon-linux2-nginx-php74.sh</code-block>
)</p>
</li>
<li data-sourcepos="31:1-32:0">
<p data-sourcepos="31:4-31:92">Connect to your server via SSH and navigate to the directory where the script is located.</p>
</li>
<li data-sourcepos="33:1-34:0">
<p data-sourcepos="33:4-33:47">Run the script with root or sudo privileges:</p>
</li>
</ol><code-block _nghost-ng-c3863015178="" ng-version="0.0.0-PLACEHOLDER"><!----><div _ngcontent-ng-c3863015178="" class="code-block ng-star-inserted"><!----><pre _ngcontent-ng-c3863015178=""><code _ngcontent-ng-c3863015178="" role="text" data-test-id="code-content" class="code-container no-decoration-radius">sudo bash server-amazon-linux2-nginx-php74.sh
</code></pre><!----><!----><!----><!----></div><!----></code-block><ol data-sourcepos="39:1-44:0" start="5">
<li data-sourcepos="39:1-40:0">
<p data-sourcepos="39:4-39:102">The script will prompt you for a project name. Enter the name you want to use for your web project.</p>
</li>
<li data-sourcepos="41:1-42:0">
<p data-sourcepos="41:4-41:79">The script will automatically install and configure the required components.</p>
</li>
<li data-sourcepos="43:1-44:0">
<p data-sourcepos="43:4-43:133">Once the script finishes successfully, you can access your web project by entering the IP address of your server in a web browser.</p>
</li>
</ol><p data-sourcepos="45:1-45:12"><strong>Example:</strong></p><p data-sourcepos="47:1-47:131">If the IP address of your server is <code>123.45.67.89</code>, you can access your project by entering <code>http://123.45.67.89</code> in a web browser.</p><p data-sourcepos="49:1-49:18"><strong>Customization:</strong></p><p data-sourcepos="51:1-51:70">You can customize the script to suit your needs. For example, you can:</p><ul data-sourcepos="53:1-56:0">
<li data-sourcepos="53:1-53:25">Change the project name</li>
<li data-sourcepos="54:1-54:29">Install additional software</li>
<li data-sourcepos="55:1-56:0">Modify the Nginx or PHP configuration</li>
</ul><p data-sourcepos="57:1-57:10"><strong>Notes:</strong></p><ul data-sourcepos="59:1-62:0">
<li data-sourcepos="59:1-59:88">Be sure to read the script carefully before running it to understand its implications.</li>
<li data-sourcepos="60:1-60:108">The script may require additional software to be installed. Confirm these installations before proceeding.</li>
<li data-sourcepos="61:1-62:0">If you encounter any issues while running the script, please refer to the documentation or contact a professional for assistance.</li>
</ul></div>
