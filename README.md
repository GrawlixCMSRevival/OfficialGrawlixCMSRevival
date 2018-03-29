<p>There are some repos on GitHub currently supporting the development of the Grawlix CMS. Very grateful for them, but going forward, this repo is going to serve as the official repo for Grawlix CMS development. Nothing personal.</p>


# Welcome to the Grawlix CMS Revival. This is the official repo hub for the revival of the Grawlix CMS for webcomic hosting.
For those unaware, the Grawlix CMS is a tool that helps comic artist publish and manage their own website to host their webcomic without needing to learn any code. Follow along with this readme to get started.

# Requirements
The Grawlix CMS requires a web host with PHP5 and MySQL. You’ll need a database on the host before you install the system — check your host’s control panel for details. You will also need a code editor like [Sublime Text](https://www.sublimetext.com/), [Atom](https://atom.io/), or [Notepad++](https://notepad-plus-plus.org/), and an FTP app like [FileZilla](https://filezilla-project.org/) or [Transmit](https://panic.com/transmit/) for easy transfer of your files to your server. You may also use your webhost's built in FTP or code editing tools.

* [Learn more about the requirements.](http://www.getgrawlix.com/docs/1/requirements) 
*<a href="http://www.thedaemoschronicles.com/grawlix-cms-setup-walkthrough/">here</a> New to FTP and web hosting?. [New to FTP and web hosting?] (http://www.thedaemoschronicles.com/grawlix-cms-setup-walkthrough/) Check out our easy to follow walkthrough on installing the Grawlix CMS by Jordan Rodriguez
* Run into a bug? [Report it](http://www.grawlixdevblog.com/bugs-report/)

# Installating the Grawlix CMS for the first time
<ul>
  <li>1.Everything you need to know to install and run the Grawlix CMS can be found [here.](http://www.thedaemoschronicles.com/grawlix-cms-setup-walkthrough/)</li>
  <li>2. Download the latest version from the repo to get started.</li>
  </ul>

# Upgrading from to 1.5.1
1. Make a backup of your site and, if possible, your database.
2. Upload the _system and _admin folders to your site, replacing the old versions.
3. Upload the functions.inc.php and index.php files into your site’s root directory.
4. Copy the new pattern files from any of the included themes into your current theme folder.
5. Go to your admin panel and follow the update prompt at the top of the screen.
6. When it’s done, delete the script _upgrade-to-1.3.php in your _admin folder.
Among other changes and fixes, versions 1.3 and 1.4 make significant changes to static pages. Check out your site’s static pages to be sure everything moved OK.
7. All of this will be covered in the README file in the grawlix-1.5.1.zip

# More info & support
<ul>
  <li>*[Read the docs](http://www.getgrawlix.com/docs)</li>
  <li>*[Follow the devblog](http://www.grawlixdevblog.com/)</li>
  </ul>

— Grawlix CMS Revival Team
