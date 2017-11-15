<h1><em>SuperRs-Kitchen-With-Binaries -</em> &nbsp; &nbsp; <a href="https://paypal.me/e1adkarak0"><img src="https://www.paypalobjects.com/webstatic/mktg/Logo/pp-logo-100px.png" alt="PayPal Donation"></a></h1>
<h2><em>The free version + binaries + updatable</em></h2>

<img src="screenshot1.png" alt="" /><br/>

<h3>How To Use?:</h3>
Download directly to your (vm-)linux machine using: <code>wget --no-check-certificate "https://github.com/eladkarako/SuperRs-Kitchen-With-Binaries/archive/master.zip"</code>,<br/>
and extract it using <code>unzip "SuperRs-Kitchen-With-Binaries-master.zip"</code> (it will create a new <code>SuperRs-Kitchen-With-Binaries-master</code> folder).<br/>
You can check for updates using the menu or use git to get the latest script(s) version. You can also use it "AS IS".

<hr/>

<h3>How To Keep It Updated?:</h3>
To update (soft update) - use the menu,<br/>
it will take care of binaries (mostly).<br/>
<br/>
To update (hard update) - remove the <code>_</code> prefix from <br/>
<code>_.git</code> and <code>_.gitignore</code> and run from inside the folder:<br/>
<pre>
git submodule foreach git clean -fdx 
git clean -fdx 
git clean -d -fx -- "" 
git submodule foreach git pull origin master 
git pull --recurse-submodules 
git submodule update 
git submodule update --recursive 
</pre>
<br/>
Download the <strong>latest smali</strong> from <a href="https://bitbucket.org/JesusFreke/smali/downloads/">bitbucket.org/JesusFreke/smali/downloads/</a><br/>
and <code>oat2dex.jar</code> from <a href="https://github.com/testwhat/SmaliEx/releases/">github.com/testwhat/SmaliEx/releases/</a>.<br/>
rename <code>.git</code> back to <code>_.git</code> and <code>.gitignore</code> to <code>_.gitignore</code>.<br/>
<br/>
<hr/>
<br/>
<img src="work_with_recovery_flushable_firmwares_in_zip_copy.png" alt="" /><br/>
<img src="work_with_recovery_flushable_firmwares_in_zip_menu1.png" alt="" /><br/>
<img src="work_with_recovery_flushable_firmwares_in_zip_menu2.png" alt="" /><br/>
<br/>