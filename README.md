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


<div _ngcontent-ng-c3190845649="" class="markdown markdown-main-panel ui-v2-enabled" dir="ltr" style="--animation-duration: 600ms; --fade-animation-function: cubic-bezier(0.05, 0.7, 0.91, 1);"><h2 data-sourcepos="1:1-1:31" class="">Purpose of the shell script centos7_php80.sh</h2><span>
</span><p data-sourcepos="3:1-3:20"><strong>Primary Purpose:</strong></p><span>
</span><ul data-sourcepos="5:1-5:39"><span>
</span><li data-sourcepos="5:1-5:39"><strong>Automates the setup of a web server environment for PHP projects on CentOS 7 and compatible systems.</strong></li><span>
</span></ul><span>
</span><p data-sourcepos="7:1-7:14"><strong>Key Tasks:</strong></p><span>
</span><ol data-sourcepos="9:1-14:38"><span>
</span><li data-sourcepos="9:1-9:64"><strong>Checks for root privileges and verifies OS compatibility.</strong></li><span>
</span><li data-sourcepos="10:1-14:38"><strong>Installs essential packages:</strong><span>
</span><ul data-sourcepos="11:4-14:38"><span>
</span><li data-sourcepos="11:4-11:21"><span>Nginx web server</span></li><span>
</span><li data-sourcepos="12:4-12:12"><span>PHP 8.</span><span>0</span></li><span>
</span><li data-sourcepos="13:4-13:51"><span>PHP extensions (mbstring,</span><span> xml,</span><span> gd,</span><span> zip,</span><span> redis)</span></li><span>
</span><li data-sourcepos="14:4-14:38"><span>Composer (PHP dependency manager)</span></li><span>
</span><li data-sourcepos="15:4-15:38"><span>Node.</span><span>js and pm2 (process manager)</span></li><span>
</span><li data-sourcepos="16:4-16:33"><span>Redis (in-memory data store)</span></li><span>
</span></ul><span>
</span></li><span>
</span><li data-sourcepos="17:1-19:51"><strong>Configures Nginx and PHP-FPM:</strong><span>
</span><ul data-sourcepos="18:4-19:51"><span>
</span><li data-sourcepos="18:4-18:66"><span>Sets user and group ownership for Nginx and PHP-FPM processes</span></li><span>
</span><li data-sourcepos="19:4-19:51"><span>Tunes PHP-FPM settings for optimal performance</span></li><span>
</span></ul><span>
</span></li><span>
</span><li data-sourcepos="20:1-24:39"><strong>Sets up a new project:</strong><span>
</span><ul data-sourcepos="21:4-24:39"><span>
</span><li data-sourcepos="21:4-21:29"><span>Prompts for project name</span></li><span>
</span><li data-sourcepos="22:4-22:53"><span>Creates Nginx configuration file for the project</span></li><span>
</span><li data-sourcepos="23:4-23:40"><span>Creates project directory structure</span></li><span>
</span><li data-sourcepos="24:4-24:39"><span>Sets permissions for project files</span></li><span>
</span></ul><span>
</span></li><span>
</span><li data-sourcepos="25:1-25:5"><strong>Performs additional system configurations:</strong><span>
</span><ul data-sourcepos="26:4-30:0"><span>
</span><li data-sourcepos="26:4-26:46"><span>Adds a swap file (if not already present)</span></li><span>
</span><li data-sourcepos="27:4-27:32"><span>Sets the time zone to Tokyo</span></li><span>
</span><li data-sourcepos="28:4-28:48"><span>Installs optional tools (git,</span><span> figlet,</span><span> htop)</span></li><span>
</span><li data-sourcepos="29:4-30:0"><span>Downloads and enables a custom greeting script</span></li><span>
</span></ul><span>
</span></li><span>
</span></ol><span>
</span><p data-sourcepos="31:1-31:19"><strong>Intended Usage:</strong></p><span>
</span><ul data-sourcepos="33:1-34:92"><span>
</span><li data-sourcepos="33:1-33:114"><span>Designed to simplify the process of setting up a web server for PHP development on CentOS 7 and similar systems.</span></li><span>
</span><li data-sourcepos="34:1-34:92"><span>Can be executed with root privileges to automate the installation and configuration steps.</span></li><span>
</span></ul><span>
</span></div>

<div _ngcontent-ng-c3190845649="" class="markdown markdown-main-panel ui-v2-enabled" dir="ltr" style="--animation-duration: 600ms; --fade-animation-function: cubic-bezier(0.05, 0.7, 0.91, 1);"><h2 data-sourcepos="1:1-1:31" class="">Purpose of the shell script server-amazon-linux2-nginx-php56.sh:</h2><span>
</span><p data-sourcepos="3:1-3:88"><strong>To set up and configure a web server environment for PHP projects on Amazon Linux 2.</strong></p><span>
</span><p data-sourcepos="5:1-5:14"><strong>Key tasks:</strong></p><span>
</span><ol data-sourcepos="7:1-9:12"><span>
</span><li data-sourcepos="7:1-9:12"><strong>Check for root privileges and operating system:</strong><span>
</span><ul data-sourcepos="8:5-9:12"><span>
</span><li data-sourcepos="8:5-8:73"><span>Ensure the user is running the script with root or sudo privileges.</span></li><span>
</span><li data-sourcepos="9:5-9:12"><span>Verify the operating system is Amazon Linux 2.</span></li><span>
</span></ul><span>
</span></li><span>
</span><li data-sourcepos="10:1-12:11"><strong>Install essential packages:</strong><span>
</span><ul data-sourcepos="11:5-12:11"><span>
</span><li data-sourcepos="11:5-11:24"><span>Nginx (web server)</span></li><span>
</span><li data-sourcepos="12:5-12:11"><span>PHP 5.</span><span>6 (version can be changed if needed)</span></li><span>
</span><li data-sourcepos="13:5-13:66"><span>PHP extensions (mbstring,</span><span> gd,</span><span> mysql,</span><span> ldap,</span><span> redis,</span><span> xml,</span><span> intl,</span><span> bcmath)</span></li><span>
</span><li data-sourcepos="14:5-14:36"><span>Composer (PHP library manager)</span></li><span>
</span><li data-sourcepos="15:5-15:35"><span>Git (version control support)</span></li><span>
</span><li data-sourcepos="16:5-16:40"><span>Figlet (display ASCII art banners)</span></li><span>
</span><li data-sourcepos="17:5-17:39"><span>Htop (system performance monitor)</span></li><span>
</span></ul><span>
</span></li><span>
</span><li data-sourcepos="18:1-20:48"><strong>Configure Nginx and PHP-FPM:</strong><span>
</span><ul data-sourcepos="19:5-20:48"><span>
</span><li data-sourcepos="19:5-19:50"><span>Set up user and group for Nginx and PHP-FPM.</span></li><span>
</span><li data-sourcepos="20:5-20:48"><span>Optimize PHP-FPM settings for performance.</span></li><span>
</span></ul><span>
</span></li><span>
</span><li data-sourcepos="21:1-25:5"><strong>Set up a new project:</strong><span>
</span><ul data-sourcepos="22:5-25:5"><span>
</span><li data-sourcepos="22:5-22:48"><span>Prompt the user to enter the project name.</span></li><span>
</span><li data-sourcepos="23:5-23:49"><span>Create Nginx configuration for the project.</span></li><span>
</span><li data-sourcepos="24:5-24:41"><span>Create project directory structure.</span></li><span>
</span><li data-sourcepos="25:5-25:5"><span>Set permissions for project files.</span></li><span>
</span></ul><span>
</span></li><span>
</span><li data-sourcepos="26:1-30:0"><strong>Perform additional system configurations:</strong><span>
</span><ul data-sourcepos="27:5-30:0"><span>
</span><li data-sourcepos="27:5-27:33"><span>Create swap file (optional)</span></li><span>
</span><li data-sourcepos="28:5-28:27"><span>Set timezone to Tokyo</span></li><span>
</span><li data-sourcepos="29:5-30:0"><span>Install greeting script (optional)</span></li><span>
</span></ul><span>
</span></li><span>
</span></ol><span>
</span></div>
