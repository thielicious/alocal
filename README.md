# aLocal.js
Recent Version: v1.1<br>
&copy; 2016 by Thielicious

#### [Documentation](http:thielicious.github.io/#alocal_doc) | [Downloads](http:thielicious.github.io/#alocal_dls) | [Licence](http:thielicious.github.io/#alocal_lic) ####

---

Beginners who are not fond in such things start with XAMPP most likely. There are many other ways to fix it in almost any language or directly in host files on Windows.<br>

But this is an example for a solution in plain JavaScript: <br>

**aLocal** ('a' for auto) is a tiny JavaScript snippet which automatically updates the address bar to localhost - ready for server-side scripts. An alternativity for newbies who plan to start programming in PHP like I did..

### Install
2. Follow this [link](http:thielicious.github.io/#alocal_dls) and choose your download option.
1. Place this script in your root directory of your host.
2. Open to edit a PHP file which must be inside of the root path.
3. Embed **alocal.js** in your page header just like any other linked script<br>
    <code>
      &lt;script src="http://localhost/aLocal.js">&lt;/script>
    </code>
4. Save it and done.
<br>

### Config
- **.setPath(path)** defines the root path, default: XAMPP folder
- **.setLocal(server)** defines your server, default: localhost
- **.change()**	executes the change
<br>

### Usage
Once embedded, it's ready to perform. Simply, open a PHP file in your browser, no need to alter the annoying address bar anymore. Not a special thing but a timesaver.<br><br>

Enjoy.<br>
<br>
http://thielicious.github.io
