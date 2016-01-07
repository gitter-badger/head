to bricks, or clicks... that the question!
// for approach ownselves`s $goals.
Just do the fucking job. Consistently!

LPIC-1 In Depth и LPIC-1 Study Guide

sudo add-apt-repository -y ppa:boomaga/ppa
sudo apt-get update

sudo apt-get install boomaga






=========
<C-D> - half window up
<C-U> - half window down
<C-E> - one line down
<C-Y> - one line up 
<C-F> - one screen down 
<C-B> - one screen up	





if { 
	read book 
}
than create {
	folder, 
	mindmap,
	ankidec
	table for replay
}
else {
	do not read book	
}

=========
@todo
git
grunt
css
html
gulp
npm
bash

@vm-test
zsh
vim-plugins 
gulp
opencart
git

@init-project
	clear-html-css
	clear-wp
	clear-opencart
how to move database to localhost?



edvard de bono
движки
модули
seo
e-commerse
import-staff
export-staff
path`s
context
excel
articles
category
contacts
forms
automatization




start project 
	clear html-css (gulp-bower)
	wp project

vagrant
	install 
		vim
		zsh
		save project (git)
		start new iso )))

задачи на следующую неделю.
=========
=========
@init-project
=========
1 requirement packets
2 npm nodejs nodejs-legacy
3 npm install -g grunt-cli
4 npm install [package] --save-dev
5 must install
6 grunt, grunt-cli, grount-contrib-concat, grunt-contrib-watch, grunt-contrib-sass, grunt-sass, grunt-bower-concat, bower 
7 npm init (create package.json)
8 $grunt
8.1 greate new gruntfile.js and write module.exports function(grunt) {//tasks}
git clone http://github.com/gruntjs/grunt-init-gruntfile.git ~/.grunt-init/gruntfile
8.2.1 grunt-init gruntfule
9 bower init
=========
=========
@nodejs@npm
=========
curl --silent --location
https://deb.nodesource.com/setup_0.12 | sudo bash -


npm cache clean -f
npm install -g n 
or 
npm update npm -g
n stable - ?
sudo ln -sf /usr/local/n/varsions/node/<VERSION>/bin/node /usr/bin/node
===============================================================================
@nodejs@grunt@bower
===============================================================================
video:introducing grunt: the javascript task runner packtpublishing
npm install -g grunt-init
git clone https://github.com/gruntjs/grunt-init-gruntfile.git
~/.grunt-init/gruntfile
grunt-init gruntfile

npm init
npm install -g grunt --save-dev
video:introducing grunt: the javascript task runner packtpublishins
npm install -g grunt-contrib-concat
npm install -g grunt-contrib-sass
npm install -g grunt-bower-install
npm install -g grunt-cli
npm install -g bower (bower requires: node npm git)


export.test = "value"

aptitude install nodejs
		npm
		nodejs-legacy

!!! when add from bower packages DONT FORGET!
	>> bower init --allow-root <<
npm install -g grunt --save-dev
npm install -g grunt - -g for use grunt from bash

npm install -g bower (bower requires: node npm git)
npm install [module] --save-dev
npm install -g grunt-bower-concat --save-dev



curl -L https://npmjs.com/install.sh | sh - update npm
===============================================================================
=========
@gulp
=========
npm install -g gulp
npm install gulp --save-dev
npm init
	package.json
gulpfile.js
=========
=========
@browser-sync

npm install -g browser-sync

browser-sync start --server --files
"*/*"
browser-sync --proxy "a.ru" --files

"*/*"
==========
@vagrant 
==========
worked.box
	vim
	unzip
	nodejs - 4.2.2
	npm 3....
	php 5.4+
	apache2
	mysql-server
	phpmyadimn	
	browser-sync
	git


==========


how to backup or save vm? 
vagrant package --output [myname.box] --include a-file, b-file  
vagrant box add --name [name/box] /path/to/box/name.box



install virtualbox
install vagrant (last verstion on site)
mkdir
vagrant box add hashicorp/precise32
vagrant init hashicorp/precise32
vargant up

vagrant --provision
vagrant status
vagrant reload
vagrant reload --provision
vagrant suspend
vargant half
vagrant resume
vagrant destroy

vagrant login
vagrant share

vboxmanage box list runningvms
vboxmanage box list vms
vboxmanage box list 

vagrant provision - run scripts ?
vagrant box repackage - ?

my vagrantfile

config.vm.network "private_network", ip: "192.168.33.10"
config.vm.provision "shell", path: "install.sh"
config.vm.network :forwarded_port, guest: 80, host: 8080
config.vm.synced_folder "./www", "/var/www"


box.scotch.io - for 64

==========
vagrant for windows
==========
chocolatey - packages manager for windows
	choco install cyg-get
cyg-get openssh
cyg-get rsync
cyg-get rcursec
==================
@vagrant_error
==================
default: SSH address: 127.0.0.1:2222
default: SSH username: vagrant
default: SSH auth method: private key
default: Warning: Connection timeout. Retrying...
 solved this problem, and will answer in case anyone else has a similar issue.

What I did was: I enabled the GUI of Virtual box to see that it was waiting for input on startup to select whether I wanted to boot directly to ubuntu or safemode etc.

To turn on the GUI you have to put this in your vagrant config Vagrantfile:

config.vm.provider :virtualbox do |vb|
  vb.gui = true
end
=========
@git
=========
--staged (or --cached) 
0 /etc/gitconfig - global settings 
0 ~/.gitconfig - for user 
1 init  
1 clone [https|git|user@server]*.git /path/to/folder 
2 remote add [origin] [shortname][https|git|user@server]*.git 
3 fetch [name remote server] (must be add from git remote add) 
3 pull [shortnamerepo] master -loads files from remote repo 
4 push [shortnamerepo] master -upload files to remote repo 
add [*|file.sh] 
branch --merget - what branch merget 
branch --no-merget - see what branch not merget else 
branch -d [branchname] - delete branch (not allow if not branchet yet 
branch [branchname]
checkout -b [branchname] - create and go to branch 
checkout [branchname] - change branch 
commit - this is open vim
commit --amend - change last commit 
commit -a - this command pass 'git add' and open vim!!! 
commit -m 'inital project version'
config --list 
config --system|global 
config --system|global core.editor vim 
config --system|global merge.tool vimdiff 
config --system|global user.email "680682@gmail.com" 
Config file location
    --global              use global config file
    --system              use system config file
    --local               use repository config file
    -f, --file <file>     use given config file

diff - see what we changed before commited 
init 
log - show commits history 
log --stat= (see what you need 'git_pro' 30|31page) 
log -p -2 - show last 2 commits 
master - local branch! 
merge 
merge [branchname] 
mergetool - see which`s bit conflicted 
mv - use for rename 
origin/master - remote branch 
remote -v -see what remote (cloned) repo we have 
remote add [shortname][url] 
remote show - see info about remote repo 
reset HEAD [file] -unstage file 
rm --cached [file] 
rm [file] 
show 
show [name] 
status - see which file we change 
tag
tag -a [name] -m "comment" 
tag -s(gpg) [name] -m "comment" 
user.name "name" 
wont delete -D) 
=========

=========
@grep@bash
=========
grep	[options] pattern [file]
grep [-e]	-exstended
grep [-re]	recrusive and exstended 
grep [-ire] 'pattern' [fil]	ignorecase,recrusive, exstended
grep [-ire]-[A[n]|B[n]|[n]] 'pattern'
[file]	ignorecase,recrusive, exstended,
num
grep --f/path/to/[file]	pattern from file
grep [options][regexp] *	find in all files
' '	find string
" "	used varibles
-A --after-context=num
-B --before-context=num
-C --context=num
-num (like A&B)
-c --count (with -v invert)
-H --with-filename
-h --no-filename
-i --ignore-case
-n --line-number
-q --quiet, --silent
-r --recursive	
-s --no-messages
-v --invert-match
-w --word-regexp
-x --line-regexp
=========

=========
@find
=========
find [where]/[what][keys]
example 
find . -name '*html'

-type d - find dir
-type f - find files
find . -name [expression] -print>[name] &
find / -name [query] -print
find /etc -type d -print 2> /dev/null (2>> - add in error file)
find / -name [query] -print 2> /dev/null
find  /usr/bin/ -amin -2 -print
find /sbin/ -perm 750 -print

. - find in current cataloge
/ - find in /
~ - find in home cataloge
find . | xargs grep '680682' -ls
find [./~] -name "what search" -print
find . ! -user [username] - show all what not belong to [username]
find . -size [+|-]10M ( if + more if - less)
b - 512-byte blocks (by default)
c -bytes (c - charachters)
k - kilobytes
M - megabytes
G - gigabytes

find . -type []
f - file
d - directory
l - symbol link
b - special file of block type
c - special file of symbol type
p - FIFO
s - socket	
=========
@tar@zip
=========
-c - make archive
-x - extract from archive
-d - find differents between archeive
-u - update archive -r - add to archive
-d - del from archive
-t -view what in archive
-f - (name of archive) file archive - use archive file or device ARCHIVE
-v - verbose verbosely list files precessed 
-j - bzip2
-z - gzip
tar -c *.txt | gzip -c > myfiles.tar.gz -make tar archive	

tar czvf [name.tar.gz] * (if all) or name of files which need put to archive
tar xzvf [name.tar.gz] [name from archive]
tar xvf  [name.tar] - extract from tar
gunzip -c [name.tar.gz] | tar x - unziping
unzip -d
gzip myfile - put in the archive
=========
@wordpress
=========
Для WordPress действуют следующие правила:

    Файлы должны быть 664
    Папки должны быть 775
    Файл wp-config.php должен быть 660

<html>
<head></head>
<body>
<div id="page" class="hfeed site">	
<a class="skip-link screen-reader-text" href="#content">Skip to content</a>

<header 
id="masthead"
class="site-header"
role="banner">

<div class="site-branding>
<h1 class="site-title">...</h1>
<p class="site-description">...</p>
</div>

<nav
id="site-navigation"
class="main-navigation"
role="navigation">

<button 
class="menu-toggle"
aria-controls="primary-menu"
aria-expanded="false">...
</button>

<div 
class="menu-main-container"

<ul
id="primary-menu"
class="menu nav-menu"
aria-expanded="false">

<li
id="menu-item-[n]
class="
menu-item
menu-item-type-taxonomy
menu-item-object-category
menu-item-has-children
menu-item-[n]
aria-haspopup="true">

<a href="#">...</a>

<ul li a ...

</ul>
</div>
</nav>
</header>

<div
id="content"
class="site-content">
...
<div
id="content"
class="site-content">
...

<div
id="content"
class="content-area">...</div>
<div
id="secondary"
class="widget-area"
role="complementary">...</div>
</div>

<footer
id="colophon"
class="site-footer"
role="contentinfo">


</footer>


=========
=========
@vim_shortcut
=========
vit - select between tags
vat - select with tags
va" - select between ""
viw - select word

<C-D> - half window up
<C-U> - half window down
<C-E> - one line down
<C-Y> - one line up 
<C-F> - one screen down 
<C-B> - one screen up	

H - to up window
M - to middle window
L - to bottom window 
* - to next 'word' at cursor # - to preveous 'word' at cursor

`. to last change line

w - > first letter
b - < first letter
e - > last letter
ge - < last letter
^ - - go to start of line
$ go to the end of line
fx - go to the 'x' in string	(3fl - go to three of 'l')
Fx - go to the 'x' in left
tx - go to the one character before 'x'
Tx - go to hte one charecter previous 'x'
=========
@vim_resizing
=========
:resize -50 (50 - count of string) 
:vertical resize [N] - resize window verticale
:10 new - new split in 10 size
=========
@vim_folding
=========
zf<motion>
[N]zF
zo - open up a flden line
zc - close a fold again
zn - unfold everything
zi - toggle all folds
zd - delete a fold
ze - eliminate all folds

Nested folds
zm - increase the fold level (one level more foldy)
zM - maximize the foldedness
zr - reduce foldedness
zR - minimmize all foldedness
=========
@vimregexp
=========
:range s[ubstitute]/pattern/string/cgiI
question|answer|#tag|
c|confirm each substitution|#vimregex#search&replace|
g|replace all occurrences in the line (without g - only first)|#vimregex|
i|ignore case for the pattern|#vimregex|
I|don`t ignore case for the patter|#vimregex|
/pattern/[n]+[1]
	/e+1
?/pattern/-2
=========
@ppa
=========
curl
python g++ make
build-essential
libssl-dev
software-properties-common 
curl -o-
htpps://raw.githubusercontent.com/creationix/nvm/v0.29.0/install | sh

python-software-properties - for add add-apt-repository

add-apt-repository ppa:ondrej/php5
add-apt-repository ppa:ondrej/php5-oldstable
add-apt-repository ppa:chris-lea/node.js
add-apt-repository ppa:zeal-developers/ppa
if crach -rm appmenu-qt5

sudo add-apt-repository ppa:foobnix-team/foobnix-player
sudo add-apt-repository -y ppa:boomaga/ppa
sudo add-apt-repository ppa:shutter/ppa
=========
@anki
=========
{{Front}}
{{Back}}
{{Tags}}
{{Type}}
{{Deck}}
{{Card}}
.card1 { background-color: #161616; }
.card
=========

=========
@ssh
=========
ls -al ~/.ssh	see what keys exsist
ssh-keygen -t rsa -b 4096 -C
"680682@gmail.com"	new key
eval "$(ssh-agent -s)"  add your key to
the ssh-agent
=========
=========
@css
=========
'line-heigh - font-size'
text-transform: uppercase;
font-weight: 100-900;

=========
@css_rwd
=========
@media (min-width: 100px;) and (max-width: 200px;) {.test {} .test {} }
=========
=css=blocks-element
=========
css=blocks elemets
address,blockquote,div,dl,dt,dd,fieldset,form,h1-h6,li,ol,p,pre,table,ul
=========
=css=string-element
=========
a,abbr,b,bdo,br,cite,code,dfn,em,i,img,input,kbd,label,q,s,select,small,
span,strong,sub,sup,textarea,var
=========
=css=block-model
=========
if [width] and [height] not put then :auto; (for width max width, for height -
	height of content)
padding 
cancel of collapse true for: web_meregevish_2011 121page

margin 0 0 0 0
1	all sides   
2	0 (up-down) 0 (left-right)	
3	0 (up) 0 (left-right) 0 (down)
4	0 0 0 0 (up right down left)


box-shadow: 0 0 20px rgba(0,0,0,0.7);
1	inset - add shadow in element 2	horisontal - 5px(right) -5px(left) 3	vertical- 5px(down) -5px(up)
4	glow - 0 sharpen
5	stratch - 5px (stratch) -5px (squeezle)
6	color - rgba(0,0,0,0.7

border:border-width||border-style||border-color||inherit
border-style [dotted|dashed|solid|double|grove|ridge|outset]
=========
=css=selectors
=========
* - universal selector
.class #ID - .class or #id selector
.class!,!.class
=css=atributes
a[title] - change if have atribute [title]
a[class="myclass"]
a[title][class="myclass"]
a[title][class~="myclass"]
a[href*="google"]
=========
=css=selectors=potomki
=========
ol > li
.child03 + .child - after .child03
.child03 ~ .child - all after .child03 
:nth-child(odd|even|<N>|<expression>|){...}
<expression>
(2n+1) - odd
(2n) - even
visited:
link:active
link:focus

first-of-type
first-child
descendant
child
nth-child
adjacent sibling
general sibling
first-line
nth-of-type
last-of-type
=========
=css=prefix
=========
-webkit-box-sizing: border-box;
   -moz-box-sizing: border-box;
        box-sizing: border-box;
			- include [padding] and [border] BUT not margin
=========
=css=other

@import url("stylesheet.css");
@import ("stylesheet.css");
				add in head genelral [stylesheet.css]
=========
=html
=========
<!DOCTYPE html> - doctype of html5
<link rel="stylesheet" type="text/css" href="stylesheet.css" media="screen" />
<img src="path/to/file.jpg" alt="name" title=""name_of_title/>
=========
=bootstrap
=========
col-lg-xx >= 1200px
col-md-xx >= 992px
col-sm-xx >=768px
col-xs-xx <=768

col-xx-pull-xx - right
col-xx-push-xx - left
col-xx-offset-xx - margin-left

visible-md visible-lg

form
=========



some=
===============================================================================

===============================================================================
=bash.command=[command]
===============================================================================
===============================================================================
=bash
===============================================================================
chenge bash
chsh -s /bin/bash
where is bash? 
echo $BASH
where is shall
echo $SHELL
===============================================================================
=bash.editing
===============================================================================
<C-l>	clear screen and put command to top	bash_editing
<C-x>	go right go left	bash_editing <C-a>	move to ^	bash_editing
<C-e>	move to $	bash_editing
<C-u>	delete left side	bash_editing
<C-k>	delete right side	bash_editing
<C-y>	past from <C-[u|k]>	bash_editing
<ESC-.>	past last word from last command	bash_editing
<C-b>	move one character to left	bash_editing
<C-f>	move to one character rigth	bash_editing
<C-t>	convert two symbols	bash_editing
<ESC-t>	convert two word	bash_editing
<ESC-c>	change register of first symbol and go \s	bash_editing
<DEL>	delete symbol from left of cursor	bash_editing
<C-d>	delete symbol under cursor	bash_editing
<ESC-l>	convert uppercase to lowercase	bash_editing
<ESC-u>	convert lowercase to uppercas	bash_editing
<ESC-?>	list of possible ends	bash_editing	
<esc-/> list of possible ends	bash_editing
and more	 (all list can see in Шевель А Обработка текстов 47стр).	bash_editing
===============================================================================
=bash.bible_of_user_2012
===============================================================================
/proc/meminfo
init - first process which run other processes
/etc/inittabs /etc/init.d (dir)- show process which load after start system
/etc/rcX.d - scripts which run 
coreutils - программы обработки файлов, программы манипулированием текста,
программы управления процессами
terminfo
/etc/passwd - user:x:501:501:full_name:/home/rich:/bin/bash
/etc/[bashrc][bash.bashrc] - global settings of bash
echo $[PS1][$PS2

===============================================================================
@bash_scripting_test
===============================================================================
test	for condition not 0 if command return 1 then 'if-then' not execute.	=bash.scripting.test
n1 -eq n2	=	=bash.scripting.test
n1 -ge n2	>=	=bash.scripting.test
n1 -gt n2	>	=bash.scripting.test
n1 -le n2	<=	=bash.scripting.test
n1 -lt n2	<	=bash.scripting.test
n1 -ne n2	not equal	=bash.scripting.test
str1 = str2	=	=bash.scripting.test
str1 != str2	str1 not equal str2	=bash.scripting.test
str1 < str2	<	=bash.scripting.test
str1 > str2	>	=bash.scripting.test
-n str1	have more then zero	=bash.scripting.test
-z str1	have zero	=bash.scripting.test
-d	check if catalog exsist	=bash.scripting.test
-e	check if file exsist	=bash.scripting.test
-f	check if file exsist and it file	=bash.scripting.test
-rc	heck if file exsist and make for writable	=bash.scripting.test
-s	check if exsist and not empty	=bash.scripting.test
-w	check if exsist and can use for write	=bash.scripting.test
-x	check if exsist and can use for execute	=bash.scripting.test
-O	check if file belong current user	=bash.scripting.test
-G	check if file exsist and his group by default like current user	=bash.scripting.test
file1 -nt file2	check what 'file1' more new then 'file2'	=bash.scripting.test
file1 -ot file2	check what 'file1' more old then 'file2'	=bash.scripting.test
exec bash	restart bash	=bash.scripting.test
===============================================================================
@bash_scripting_iffi
===============================================================================
if (if error go use else if all ok go use then) then-else-fi	iffi	
if [\s!command\s] && [\s!command\s]	AND if both command TRUE next ELSE
=bash.scripting.iffi
if [\s!command\s] || [\s!command\s]	OR if any command TRUE next ELSE
=bash.scripting.iffi
if test [\s!command\s!]	?
=bash.scripting.iffi
if [command] (return 0) then [commands] (returned not 0 = pass command (go to
		=bash.scripting.iffi
		next) then [commands] fi	?
	=bash.scripting.iffi
	if [command] (return 0) then [commands] else [commands] fi	?
	=bash.scripting.iffi
	if [command] (return 0) elif [commands] then [commands] else fi	?
	=bash.scripting.iffi
===============================================================================
@bash@grep
===============================================================================
grep	[options] pattern [file]
grep [-e]	-exstended
grep [-re]	recrusive and exstended 
grep [-ire] 'pattern' [file]	ignorecase,recrusive, exstended
grep --f/path/to/[file]	pattern from file
grep [options][regexp] *	find in all files
' '	find string
" "	used varibles
-A --after-context=num
-B --before-context=num
-C --context=num
-num (like A&B)
-c --count (with -v invert)
-H --with-filename
-h --no-filename
-i --ignore-case
-n --line-number
-q --quiet, --silent
-r --recursive	
-s --no-messages
-v --invert-match
-w --word-regexp
-x --line-regexp
===============================================================================
@bash@ln
===============================================================================
symbol and hard links - read more about thih


=sass
===============================================================================
install ruby
	gem install sass
compiling
	sass input.scss output.css

Grunt — это инструмент для сборки проектов из командной строки с использованием
modules (from grunt)
grunt-contrib-watch
	contrib-clean
задач. 
Bower -  is a package management system for client-side programming on the
World Wide Web. It depends on Node.js and npm. It works with git and GitHub
repositories.

--save-dev & --save
Компиляторы-транспиляторы-трансляторы (типа Coffee, LESS, Jade), тест-раннеры,
стайл-чекеры и линтеры (mocha, chai, karma, (js|es)lint, jscs), плагины для
таск-раннеров (grunt-contrib-watch, gulp-jade) — все это обычно ставится как
--save-dev, потому что нужно только тем, кто контрибьютит в этот проект,
работает с его кодом.

Библиотеки и фреймворки (expressjs, jquery, backbone), на основе которых
работает ваш код, без которых ваш код не запустится у его потребителя —
ставятся как --save. 
===============================================================================
@opencart
===============================================================================
for 2.0 need installed
php5-mcrypt 
ln -s /etc/php5/conf.d/mcrypt.ini /etc/php5/mods-available (put mcrypt.ini from mods to /etc/php5/apache2/conf.d/ and ln)
php5enmod mcrypt
service apache2 restart	
structure of site
admin/config.php - http[s] dir db
index.php
recquire_onece('startup')
===============================================================================
@opencart_header
===============================================================================
./catalog/controller/common/header.php
./catalog/view/theme/default/template/common/header.tpl
./catalog/language/english/common/header.php
./admin/controller/common/header.php
./admin/view/template/common/header.tpl
./admin/language/english/common/header.php

===============================================================================
@opencart_premissions
===============================================================================
/var/www/a.ru/config.php 	
/var/www/a.ru/admin/config.php 	

5. Please make sure you have set the correct permissions on the directories list below.
Directories 	Status
/var/www/a.ru/system/cache/ 	
/var/www/a.ru/system/logs/ 	
/var/www/a.ru/system/download/ 	
/var/www/a.ru/system/upload/ 	
/var/www/a.ru/image/ 	
/var/www/a.ru/image/cache/ 	
/var/www/a.ru/image/catalog/ 	
/var/www/a.ru/system/modification/ 	Unwritable

===============================================================================
@apache2@hosts
===============================================================================
/etc/apache2

commands
apache2
apache2ctr stasus - see what status
apachectl configtest - check the configuration files
apachectl -V -show where all installed 
httpd_root="/etc/apache2"
server_config_file="apache2.conf"

a2ensite [sitename]
sudo /etc/init.d/apache2
start
restart
apachectl -k stop

example site *.conf file
/etc/apache2/sites-available/*.conf

<VirtualHost 127.0.1.2:80>
ServerAdmin 123@site1.ru
ServerAlias site1.ru
ServerName site1.ru
DocumentRoot /var/www/site1.ru
</VirtualHost>

if error ah00558 - add string 'ServerName localhost' in end of
apache2.conf

put in apache2.conf
Include /etc/phpmyadmin/apache.conf
add string 'ServerName localhost'
===============================================================================
@lamp@hosts@mysql
===============================================================================
mysql-server 

php5
php5-mysql
php5-mcrypt
php-gd
php5-curl
libcurl3
curl

apache2
libapache2-mod-php5
libapache2-mod-auth-mysql

phpmyadmin

install lamp sudo apt-get install lamp-server^
install apache
1 sudo apt-get install apache2
test apache
2 test http://localhost/
install php
3 sudo apt-get install php5 libapache2-mod-php-5
test php
4 sudo /etc/init.d/apache2 restart
5 sudo vim /var/www/testphp.php
<?php phpinfo(); ?> (in html folder)
install mysql
6 sudo apt-get install mysql-server
7 gksudo gedit /etc/mysql/my.cnf (if need change ip addres in string
bind-address = 127.0.0.1
8 sudo apt-get install libapache2-mod-auth-mysql php5-mysql phpmyadmin
login localhost/phpmyadmin	

===============================================================================
@xorg
===============================================================================
startx - start
pkill -15 Xorg

man Xorg
x11 - /usr/share/X11
display manager - auntification users, registrations,start scripts, run x-server
window manager
wiget library
.login 
./xsession - 
1 see what display manager work is now - /etc/X11/default-display-manager (/usr/sbin/mdm):
possible wm manager 

=update-alternatives --config x-session-manager

===============================================================================
@i3
===============================================================================
xrandr --current - see what is monitor
mod1 = alt
mod1+enter new window
a - focus parent
s - stacked layout
d - dmenu
f - fullscreen
mod1+j - left
mod1+k - down
mod1+l - up
mod1+; - right

mod1+e, w, s.
mod1+f - fullscreen

mod1+d - dmenu

mod1+shift+w, q
mod4 = win
shift+mod1

# reload the configuration file
bindsym $mod+Shift+c reload
===============================================================================
=mysql
===============================================================================
mysql -u root
mysql> SET PASSWORD FOR 'root'@'localhost' =
PASSWORD('yourpasswrd');
mysql -u root -p

Install
sudo apt-get install mysql-server (if need php5-mysql)
Install nginx
sudo apt-get install nginx
test in brawser localhost
error 1045 (28000): access denied for user 'lenovo'@'localhost' (using

what is it  - mysql workbench

===============================================================================
=mysql.language
mysql>bd>table>rows
mysql -u root -p
show databases;
crate database [name];
create table [name_table] ([name_colunm] [int] [not null] [auto_increment]
	[primary key]) engine=innodb;
-----------------------------------
|field|type|null|key|default|extra|
-----------------------------------
|name |int |not |pri| null  |autoi|
-----------------------------------
alter table [name_table] add [name_column] int after [name_column];
alter table [name_table] change [name_column] [new_name_column] text;
alter table [name_table] drop [name_column];

show tables;
describe [table]	
use database [name];
describe [table_name];
select * from [table_name];
drop datebase [datebase]
insert into [db_name](`author`,`title`,`type`,`year`) values ('mark twain', 'the adventures of tom sawer', 'fiction','1876');	перечисление столбцов не обязательно.

select [colomn],[column], from [table];
select count(*) from joke;

insert into [table_name] set
[name_column] = '[data]',
[name_column] = '[data]';

insert into [table_name]([name_column],[name_column]) values ([data],[data]);

curdate() - current date
Наиболее востребованные команды		
select insert update delete
ALTER	Внесение изменений в базу данных или таблицу
BACKUP	Создание резервной копии таблицы
\c	Отмена ввода
CREATE	Создание базы данных или таблицы
DELETE	Удаление строки из таблицы
DESCRIBE	Описание столбцов таблицы
DROP	Удаление базы данных или таблицы
EXIT (CTRL-C) 	Выход
GRANT	Изменение привилегий пользователя
HELP (\h. \?)	 Отображение подсказки по элементу
INSERT	Вставка данных
LOCK	Блокировка таблицы (таблиц)
QUIT (\q)	То же самое, что и EXIT
RENAME	Переименование таблицы
SHOW	Список сведений об элементах
SOURCE	Имя_файла Выполнение команд из файла имя_ файла
STATUS (\s)	Отображение текущего состояния
TRUNCATE	Опустошение таблицы
UNLOCK	Снятие блокировки таблицы (таблиц)
UPDATE	Обновление существующей записи
USE	База^данных Использование базы__данных
int unsigned	делает столбец способным принять целое число достаточно большое  для того что бы в таблице могло храниться более 4 млрд записей
auto_increment	заставляет установить уникальное значение в каждой строке
key	столбец с авто приращением полезно использовать в качестве ключа

===============================================================================
=map
db_login.php
pdo.php
index.html.php
echo [some think]
index.php	
===============================================================================

===============================================================================
=php.error
===============================================================================
PHP : Включить показ предупреждений и ошибок PHP
Включение вывода всех ошибок и предупреждений в файле php.ini

error_reporting = E_ALL
display_errors = On
display_startup_errors = On


Включение вывода всех ошибок и предупреждений в коде PHP-скриптов
Включить вывод уведомлений и предупреждений можно, добавив в начало нужного
.php файла следующие строки:

ini_set('error_reporting', E_ALL);
ini_set('display_errors', 1);
ini_set('display_startup_errors', 1);



Включение вывода всех ошибок и предупреждений в файле .htaccess

php_value display_errors 1
php_value display_startup_errors 1
php_value error_reporting E_ALL

===============================================================================
=php.pear
===============================================================================
wget http://pear.php.net/go-pear.phar
php go-pear.phar
pear remote-list
pear list - all installed package
pear config-get php_dir - see where installed package
pear config-show


two part 
PHP fondation classes - oop hight quality code
pect - write on c

xdebug
aptitude install php5-xdebug
===============================================================================
@php
===============================================================================

php --ini
install php
php5-fpm,php5-mysql

install pear

wget http://pear.php.net/go-pear.phar
php go-pear.phar
pear remote-list

pdo
phpfaq.ru/pdo
http://habrahabr/post/126664
mysqli

DB
MDB2

=php.language

<?php ?>
print("hello world, again");
$var = [n]
'_' - text string
need ecraned \' and \\ 

"_" - cant contain $var[iable]

superglobal massive

$GLOBALS
$_SERVER

$_GET
$_POST

$_COOKIE
$_FILES
$_ENV
$_REQUEST
$_SESSION
===============================================================================
@php_smarty - template engine
===============================================================================
smarty.class.php - /usr/share/php/smarty3
===============================================================================
@php.cgi
===============================================================================
http:example.com/file.php?[variable]=[value]&[variable]=[value]
===============================================================================
@php.function
===============================================================================
include -add some code to page
strlen|mb_strlenj- count symbols
ltrim|rtrim|trim - delete symbols
str_replace - replace and del symbols
substr|mb_substr - except symbols
explode - explode string
implode - implode array to string
preg_split - explode by regex
strtolower|strtoupper - to low-up case
ucfirst|ucwords - low-up first letter
substr_count - count how much [n] in string
min|max - which min-max num in string
in_array -check if [n] exsist in array
array_reverse
rand - ramdom
range - range of element to array
htmlspecialchars($var, ENT_QUOTES, 'utf-8') - html to &[nn]
exec = delete insert update
in PDOStatement name  execute
===============================================================================
@php_type of data
===============================================================================
is_bool()
is_integer()
is_double() with swiming dot
is_string()
is_object()
is_array()
is_resource()
==============================================================================
@php.if
===============================================================================
if (some) {execute}
if ([some] and [some]) {execute}

if (some) {execute}
/else 

$count = 1;
while ($count <= 10) { echo "$count "; ++$count; }

for ($count = 1; $count <= 10; ++$count) { echo "$count "; }

$myobject = new someclass(); //create object
$myobject->someproperty = 123; // add to property value
echo $myobject->someproperty; // take vallue of property
php.ini
magic_quotes_gpc - off/on
===============================================================================

@php_operators
===============================================================================
Операторы присваивания			
=	$n = 42	
+=	$n += n	
-=	$n -= n	
*=	$n *= n	
/=	$n /= n	
./	$n .= n	Можно объединить строки
%=	$n %= n	
Операторы сравнения			
==	$n == 42	Равно
!=	$n != 42	Не равно
>	$n > 42	Больше чем
<	$n < 42	Меньше чем
>=	$n >= 42	Больше или равно
<=	$n <= 42	Меньше или равно
Логические операторы			
&&		AND
and		Низкоприоритетное AND
||		OR
or		Низкоприоритетное OR
!		NOT
Hor		Исключающее OR
Математические операторы		Возможно использование скобок. Приоритет одних математических операций над другими и изменение приоритетов при использовании скобок в арифметических выражениях соответствуют обычным математическим правилам.	
+		Сложения
- 		Вычитания
*		Умножения
/		Деления
%		Модуль (остаток от деления)
++		Инкремента(приращение) 
!есть значение где стоит, перед оператором или после
If (++$x == 10) echo $x; #сначало добавит, потом проверит
--		Декремента(отрицательное приращение)
!есть значение где стоит, перед оператором или после
If ($x-- == 0) echo $x; #сначало проверит, потом минусует  

++$n - сначала добавит
.= add to end of $var next value
===============================================================================
=rest
===============================================================================
===============================================================================
@javascript=js
===============================================================================
x = 0; // now the variable x has the value 0
x = 1; // numbers
x = 0.01; // sust one number type for integers and reals
x = "hello world"; // strings of text in quotation marks
x = 'javascript'; // single quote marks also delimit strings
x = true; //boolean values
x = false; //the other boolean value
x = null; //null is a special value that means "no value"
x = undefined // undefined is like null

var book = {
	tipic: "javascript",
	fat: true
};
//access the properties of an object . or []:
book.topic
===============================================================================
@jquery
===============================================================================
<script language="javascript">
$(document).ready(function(){
	$('[element|#id|.class|*').css('border','3ps solid
	black'));
});


===============================================================================
@nwjs
===============================================================================
html5.by/blog/nwjs/ - see how tool exist for database connect
===============================================================================
@anki
question\tanswer\t#tag\n
===============================================================================
Вот эта пара строк сильно экономит время на копание в .vimrc
" ## Edit .vimrc ##
map ,v :vsp $MYVIMRC<CR>
map ,V :source $MYVIMRC<CR>

take regexp string from file and find in dir/file/string (range strings)

1 find all dependent files of programm
locate
2 safe all depend files in archive
3 install to new system1 find all dependent files of programm
locate
2 safe all depend files in archive
3 install to new system
-
--------------------------
@lintree
computerhope.com/unix/overview.htm - list of commands 
vim.wikia.com/wiki/Use_vi_shortcut_in_terminal --- linux dir faq

===============================================================================
@filesystem
hierarchy standard - read more
===============================================================================
bin - containes executable of the useful Linux software or you can say command
boot - comtaines the files required on booting Linux. It also stored data related to kernel loading. It contains grub loader files also.
cdrom - cdrom
dev - all device
etc - containes configuration file to system and user package.
home - home directory for user
lib - directory contains various library which is used by different command
lost+found
media - in this directory mount removable media
mnt - also used for mounting device
opt - for all optional or additional software
proc - contains all running process information
root home for root
run
sbin - identical to /bin but contains only store executable used for system maintenance or administrative task
srv
sys
tmp - contains temporary files
usr
var - this is oppoosite of /usr directiry. contanins all variables and rightable files

===============================================================================
@bash
===============================================================================
===stdin and stdout===
stdin - keyboard (0)
stdout - if right (1)
stderr - if error (2)

info readline - important
rm prog.{exp1,exp2}
\, - match ','
; - step-by-step
&& - if true than do next step
|| - if talse than do next step
$(command) -
| - take to another program
> - take to file
>> - take to exsist file (create if it not exsist
set -o noclobber - not allow overwrite stdout in file (if exsist) if need add to .bashrc
set +o noclobber - off 
>| - overwrite file if exsist
< - take data from file

/etc/bash.bashrc

alias h='cd ~/Dropbox'
alias hd='vim ~/Dropbox/head'

=bash.special.files
/etc/passwd - take name of $home folders
/etc/profile - run when user login (if bash allowed in /etc/passwd)
$home/.bash_profile - run when user login
$home/.bashrc -run when bash start	
$home/.bash_logout -run when user logout
$home/.bash_history

can use in bash;
*,?,[...],[!...](! -any but not in []),-name(catalog of user with name), -+ -
current cataloge, -- previous cataloge

(( expression ))
[[ expression ]]
case - read more about this command and see examples

=ifs - IFS=$'\n' - off tab and \s and allow only '\n' (new line)
or can use IFS=: - and bash use : like '\n'
or can use like this IFS=$'\n':;"
=for 325
'for [var] in [list (list of values)]
do
[commands]
done
'
list="var1 var2 ..."
list=$list" var3 ..."

for state in $list
do
echo "some text $state"
for (( a = 1; a < 10; a++ )) - counts


example in C
for (i = 0; i < 10; i++)
{
printf("the next number is %d\n", i);
}
=while
while
test
command
do
other
command
done

=until
until test
commands
do

other commands
done

=break

=continue

=exit $var - use exit by variable (if need [n] to out)

=read

$? - status of end program
0 - if correct 
1 - common unknow error
2 wrong use of command
126 - cant to be use
127 command not find
128 unacepteble argument of exit
128+x nofixed error with signal x system linux
130 end of command make with <ctrl+c>
255 value of status exit-a not accept allowed range

expr - math
var1=$[100500+1] - variable with math expression ($var1) !!! only (100\3=2)!!! if need more see =bc
`[command]` - for variable
for #!/bin/bash - use ' '
" " - use if text contain '
echo -n - not \n
echo echo [some command] > bin/[file]
$HOME/bin
1 make file *.vim
echo "Hello, Vim"
source /path/to/file/*.vim
		      source % - use if *.vim open in vim

		      touch [name] && echo '#!/bin/bash/' > do2 && echo '[command] [; \| && \| || ] && chmod [name] && [name]


		      head of file - #!/bin/sh
		      make  a file rights - chmod 555 scriptname and can use !! ./scriptname at last put file to /usr/local/bin (or see allowed folders echo $PATH) for run 'scriptname'
		      run script - sh scriptname
		     * - any file in folder
		     $$ - id process of the script
		     scriptname >> add output from scriptname to file. if not exsist, make it




===============================================================================
=console=utilites
===============================================================================

Разделы man-страниц
1 выполняемые программы или команды для командной оболочки
2 обращение к операционной системе (функции предоставляемые ядром)
3 обращение к библиотеке (внутренние функции программных библиотек)
4 специальные файлы (обычно можно найти в /dev)	
5 форматы файлов и условные обозначения типа /etc/passwd
6 игры
7 прочее (включая макропакеты и условные обозначния)
8 команды по администрированию системы (обычно для root)
9 программы ядра (нетипичные)


bg &
fg
unic

nice
unnice

jobs

=sleep - run command after [n] times

apt-(get,cache) - for load and install package






dd - copy files, ano more (copy iso and more)
=sort
-n - if need sort only digt
-M	sort if month 

=lsattr - see attributes for ext2/3
=chattr - change attributes ext2/3
+[] -add 
-[] -del

-R recrusive

-a only add 
-c shatiy
-d with out dump
-I(or i) postoyanniy
-j registraion dates
-s save delete
-t  zapret sliyaniya in and file
-u undeleted
-A without update atime
-D sync update cataloge		
-S sync update
-T head of tree catalogs

===============================================================================
===============================================================================


===============================================================================
@apt-get@apt-cache@aptitude@mercurial@deb@rpm@yum@dpkg@wajig@apt-rdepends@bitbucket
===============================================================================

=rpm
rpm -Uhv [package.rpm]
	i - install
	U - upgrade and install (if not installed)
	h - see process install
	v - verbose
rpm -e [name of prgramm]

yum install 
yum remove 
yum update
yum search
yum list available
===============================================================================
dpkg - for work with deb-files
-i [package] - install
-r [package] - remove

dpkg -L [program] see where all installed files


apt-get install $(< file.txt)

aptitude -V -s install [package]
aptitude versions [package]

apt-get -V -s install [package]

apt-get install [package]
apt-get remove [package]
apt-get --purge remove [package] - remove all files
apt-get update
apt-get upgrade
apt-cache search [package]
apt-cache stats
apt-key add [file]

apt-get clean - remove installation package | all packages downloaded
in '/var/cache/apt/archives' | if in process installtion error files in
'/var/cache/apt/archives/partial'

wajig repackage
	recdownload
	dependents
на сервере без интернета устанавливаем пакеты	
	apt-get --print-uris --yes example_package >example_package.htm 
	получаем файлик со ссылками всего, что надо скачать. на компе с
	интернетом качаем
	wget -o dir::cache::archives="/media/flash" install
	example_package
	/media/flash - это место где у вас лежат скачанные пакеты

	apt-rdepends [package]
	graphviz		
	apt-get install software-properties-common

===============================================================================
===============================================================================
=repository=local=iso
==============================================================================
1. make dir
mkdir /mnt/debian-dvd
2. add to file /etc/fstab
/mnt/storage/iSO/debian-i386-DVD-1.iso /mnt/debian-dvd/ udf,iso9660 loop 0 0

3. add /etc/apt/sources.list 
deb file:/mnt/debian-dvd/ wheezy main contrib

4. mount /mnt/debian-dvd/
5. apt-get update
==============================================================================



1 mkdir /path/to/folder
2 in /etc/rc.local add
mount -t iso9660 /path/to/*iso /path/to/mount/*iso
3 /etc/apt/sources.list add 
deb file:/path/to/mount/folder stable main contrib
4 aptitude update
===============================================================================


=mount
blkid
for ide
	/dev/hda /dev/hdb /dev/hdc
	
for scsi, sata, usb
	/dev/sda /dev/sdb /dev/sdc 

=umount umount -l
fdisk - see what you cant mount
lshw - not installed
gnome-disk-utility
sfdisk - similar fdisk but more features
cfdisk - 
parted
df
pydf - impoved df (not installed)
mkdir /mnt/[foldername]

===============================================================================
=network=ifconfig=net=ping
===============================================================================
ifconfig -a - see all network device

/etc/init.d/networking [start|stop|restart]

ping -c 10 [www.google.com] - -c 10 count of pings
traceroute [www.google.com]
	-m - count of transactions
mtr - another program like 'ping and traceroute'

===============================================================================
=find=locate=mlocate=whereis=whatis=which=apropos
===============================================================================
=mlocate - base all files in system (in file upddatedb.config	


=locate - find all files and folder
		i - ignorecase
		-n [n] - see first 3 result	
		slocate - if not have root`s rights (must be installed)
		sudo updatedb - update mlocate
=whereis - find where is program
=whatis - whatis a program
=which - what is run?
=apropos [word or command] - search all man page		
man -k - apropos what?
man -k [request]
man -f [request]- short comment about command	
man -f - short comment about command	
man -u - update db man`s

===============================================================================

===============================================================================
=vim.compile
===============================================================================
apt-get build-dep vim
hg clone https://code.google.com/p/vim/ vim
./configure [-|--][some]
make
make install

1browse
perl
python
python3
ruby
lua

===============================================================================
=vim=help
===============================================================================
:options - see all 'set' options and more
add-local-help
write-local-help
runtimepath
+multi_lang (compiled)
help-writing
===============================================================================

=rename - renames multiple files using a regualar expression
===============================================================================
=rm
===============================================================================
		-r/-R -recursive
		-Rf - recursive and silent
		rm -rf [dir]
		rmdir - remove a dir
rm [filename/regexp].{exp1,exp2}
===============================================================================
===============================================================================

===============================================================================
=ls 
===============================================================================
-d - directory
--group-directories-first
-X -sort by extension file
-A - list without '.,..'
-C - list by column
-i -show inode 
-l - show hidden file and directories 
-lt - sort by last time change
-lu - sort by last time open
-lS - sort by size
-li show by number inode link by each file
-ln - show instead user`s name numbering indeficator
-lh - show file size in usefull form
-lR - show recursive files and sub files
-l -h
-l -rights
-as - show hidden directory
-a -show all files
-help | more - page-by-page view

| less - page-by-page view (up and down) support jk
ls -m - comma!
ls -R - recursive
ls -R [~|.|..]/[*|name]
ls -t -sory by time
ls -s - sort

ls -F - what is catalog
/ -dir
* -execute file
@ -symbolic link
FIFO - first in first out	
= -socket
ls --color
green - execute file
blue - catalog
magenta symbolic link/socket/audio/video/img
yellow - FIFO
red - archive
=sed -stream editor 

drwxrwxrwx - example 
d -dir or
	c - nakopitel
	b - block device
	l - symbol link
	p - named chanall
	s - socket
		
rwx -user (right in this cataloge)
rwx -group
rwx -other

=chmod - take a right
chmod [option] [mode],[mode][file]
chmod [option] [octal_mode][file]
chmod [option] --reference=rfile file

r - read
w - record
x - execute 

symbol format
[ugoa][[+-=][rwxXstugo]...],[...]

u - owner
g -group
o ?
a ?

===============================================================================
=chgrp=chown
===============================================================================
=chgrp -  change group
-R - recursive
-R [name] .* - !!! (..)
=chown - change own rights

=touch - change time access and change file and make new file
-a change only time access
-m change only time
-t set your time 
> /path/to/folder - make empty file



=ed - is an interactive file editor 

=tree - tree of directory

=pstree:   displays the processes on the system in the form of a tree diagram.




=zcat zmore - see what in archive


=unrar
rar  - must be installed

tar -zxvf example.tar.gz
w-symlinks

follow symlinks when processing in place

-i[SUFFIX], --in-place[=SUFFIX]

edit files in place (makes backup if SUFFIX supplied)

-l N, --line-length=N

=cp
cp **/*.[extension] destination_dir
=find





uname:   provides basic information about a system's software and hardware.
=w:   shows who is logged into the system and what they are doing.

=shred:   destroys files.(delete files?)

=strings:   returns each string of printable characters in files.

=whichis - find where is program
=dpkg-query -S `whichis ps` - find whichis ps

which find path is program 
which bash - /bin/bash	



		sudo su - (sudo)
		su -l [username] -change user

		kill - lill process
		killall -9 [name]

		cal[endar]

		dog - reads html,web and other RTFM (must be installed)

=cat - reads data from files
cat myfile > copy - copy myfile to copy
cat myfile >> copy - add myfle to copy

cat -n view like 'set number'
cat -b - view like 'set number' but only not empty strings 	
cat 1.txt 2.txt > 3.txt 

cat [file] | head - like head

=head - view only head (first 10 string)
-n [n] - count of view string
-c [n] - count of view bytes
ps auwx | head -15 - view first 15 string of ps
tail - view only 10 last string (can watch in real-time
		-f - (fallow)  view update info 
		-f --pid=[nnn]

		more - page-by-page view
		ps auwx | more
		more myfile
		less - what is less? less is more!
		v - start vim
		-N - view number string
		F - move 10 string forvard
		B - move 10 string back
		D - move to half screen forward
		U - move to half screen back


		tac - reads data from files in revers order
		rev

		ps --column=2 - broken page and view\print page-by-page

=echo - displays a line of text

=wc - word count	
string
words
bytes



=nl - number of line in file

=tee - copy input text to file
ls | tee text.txt - simply example	
=poweroff - poweroff

=curl - is a client to get documents/files from or send documents to a server.
=mv - rename and move file

=mc - file manager

===============================================================================
=bash=ps
===============================================================================
S - sleeping
SW - sleeping and waiting
R - running
-u -[user]

=top 
-u [user] - all process for [user]
- n 10 - show 10 process (in top!)
- K [pid] show 10 process (in top!)
- N -n +n - priority process

=pgrep - find process
-l [program] show pid 

=df:   reports the amount of space used and available on currently mounted filesystems.
du:   shows the sizes of directories and files.


=hostname:   shows or sets a computer's host name and domain name.
=print
lpstat
-t - list of printers
-d - view of default printer
-s - veiw of type connection of printer
lpt - send to default printer
lpr -P -chose priner
lpr -# [n] -number of copies
lpq - list of sended to printer
lprm - remove 
--

stat - view info about file

where are you?
pwd
how move between folders?
=cd
cd ../../.. - up to three folder
cd $OLDPWD
cd - go to /home/name folder
quickly swith between folders
/exist/folder/way pushd /other/folder
/other/folder/ popd /exist/folder/way





luakit - web-brawser
	:inspect :in
weechat - irc client					
pidgin
join [name of chennal]
/msg NickServ REGISTR password yourmail@yourmail.com
| rus-net.org		| 
| irc.freenode.net	|

=w3m
<C-m> <C-j> - go to current link
<C-t> - open current link on new tab
<ESC>-C-j - save link to file
I - save image to file

tab operation
<T> -open new tab
<C-q> - close current tab
{} - next\previous tab
<ESC-t> - popup tab selection menu
bookmark operation 
<ESC-b> - read bookmark
<ESC-a> - add current page to bookmark

H -view of help
o -option setting panel
<C-h> - view of history
D -display download list panel




gedit - text editor
xchm
vifm -file manager
mc - file manager
deadbeef - audio player 
cmus - audio player
foobnix


sudo apt-get update
sudo apt-get install foobnix

yandex br / chrome 
vimium 
firefox
vimperator
vimfx - not try yet
mplayer - videoplayer							

guake - concole launcher
gnome do - gmome do
gtile
workspace grid								

apvlv - pdf reader vim-like
zathura 
zathura-djvu
	as -besf fit to window
	bmark [n]
	blist [n]
mupdf
pdf-viewer
qpdfview
xpdf
tint - tetris for console
tetris-bsd
netris - vim-style

rtorrent
freemind - mindmapping


===============================================================================
=terminator
===============================================================================
terminator
super+R - rotate terminal clockwise
c_s+x toggle between showing all terminals and only showing the current one (maximise)
c_s+t -new tab
c_s+I -new window
c_s+e -vsplit
c_s+o -split
c_s+p -focusoprevious vils
c_s+n -focus next view
c_s+w -close active view
c_s+q -quit terminator
c_s+x -hide/restore current view 
c_s+z -zoom current view	
F11 - fullscreen							
c_s+s -hide/show scrollbar
borderless fullscreen	 -b -f

[profiles]
[[default]]
scrollbar_position = disabled
===============================================================================

pdf2djvu 


=adsys


=sysstat - no installed 
=free -   provides information about unused and used memory and swap space.
=vmstat - stat of free memory


=grub /boot/grub/menu.lst:



strace - for xz





=vim
:digraphs

vimgolf.com
http://mirnazim.org/writings/vim-plugins-i-use/ - see what need and move link to 'names links and faq`s'
add in vim_vundle russian comments and see why not work tetris.vim

---
vimrc
set ruler
set no/ignorecase - ignorecase
set ignorecase smartcase - READ MORE ABOUT THIS
set modifiable
syntax on
filetype indent on
set smartindent
set wrap -перенос длинных строк
set number
set undofile
set gdefault
set hlsearch - show non-printable sign when search
set list - show non-printable sign allways
set incsearch
set ignorecase
set showmatch
set ignorecase 
set smartcase	
set cursorline
highlight CursorLine term=bold cterm=inverse
set cursorcolumn
highlight CursorColumn term=bold ctermfg=cyan ctermbg=black
sh - go to shall. when end in shall enter 'exit'
set compatible - compatible with vi
set wildmode=list:longest - show all possible command list
set foldmethod=indent
set cursorline
any set off - try add to command prefix 'no' (example set nocursorline)
set spelllang=ru - find and set on later
undolist
set filetype=sh


put in .vimrc -   call matchadd('ColorColumn', '\%81v', 100)

this is the main configuration file for vim. It exist in two versions - global and personal.
global  
:echo $VIM (/usr/share/vim/)
personal
:echo $HOME (/home/user/.vim/)
other
so $VIMRUNTIME/syntax/hitest.vim - see a complete list of color groups.
colorscheme - colorscheme


names, links and faq`s
video 'Mastering Vim' by Damian Conway
http://www.vim.org/scripts/ - thousands of plugins
rus-linux.net/MyLDP/BOOKS/Vim/prosto-o-vim-16.html
jenyay.net/programming/tools - about vimscript (and git)
---
help.txt

tips.txt
Counting words, lines, etc.	|count-items|
Renaming files		|rename-files|
change.txt - all about change in text
help undo-persistence - about infinite undo 

help help-writing

1 The first line in a help file should have the following format:
*helpfile_name.txt*	For Vim version 7.3	Last change: 2010 June 4

2 At the bottom of the help file, place a Vim modeline to set the 'textwidth'
and 'tabstop' options and the 'filetype' to 'help'.  Never set a global option
in such a modeline, that can have consequences undesired by whoever reads that
help.


help compl-omni-filetypes
help registers
pattern.txt - pattern and search commands
usr_27 'Search commmands and patterns
usr_41.txt - write a vim script
---
plugins
unite.vim
syntastic - syntax checker
fgitive - git for vim
conque - interactive in vim
yankmatches.vim - Damian Conway
foldsearches.vim - Damian Conway
dragvisual.vim - Damian Conway

===============================================================================
		=nerdtree
===============================================================================
" NERD tree (4.2.0) quickhelp~
" ============================
" File node mappings~
" double-click,
" <CR>,
" o: open in prev window
" go: preview
" t: open in new tab
" T: open in new tab silently
" middle-click,
" i: open split
" gi: preview split
" s: open vsplit
" gs: preview vsplit
"
" ----------------------------
" Directory node mappings~
" double-click,
" o: open & close node
" O: recursively open node
" x: close parent of node
" X: close all child nodes of
"    current node recursively
" middle-click,
" e: explore selected dir
"
" ----------------------------
" Bookmark table mappings~
" double-click,
" o: open bookmark
" t: open in new tab
" T: open in new tab silently
" D: delete bookmark
"
" ----------------------------
" Tree navigation mappings~
" P: go to root
" p: go to parent
" K: go to first child
" J: go to last child
" <C-j>: go to next sibling
" <C-k>: go to prev sibling
"
" ----------------------------
" Filesystem mappings~
" C: change tree root to the
"    selected dir
" u: move tree root up a dir
" U: move tree root up a dir
"    but leave old root open
" r: refresh cursor dir
" R: refresh current root
" m: Show menu
" cd:change the CWD to the
"    selected dir
"
" ----------------------------
" Tree filtering mappings~
" I: hidden files (off)
" f: file filters (on)
" F: files (on)
" B: bookmarks (off)
"
" ----------------------------
" Other mappings~
" q: Close the NERDTree window
" A: Zoom (maximize-minimize)
"    the NERDTree window
" ?: toggle help
"
" ----------------------------
" Bookmark commands~
" :Bookmark <name>
" :BookmarkToRoot <name>
" :RevealBookmark <name>
" :OpenBookmark <name>
" :ClearBookmarks [<names>]
" :ClearAllBookmarks
===============================================================================
===============================================================================

vim-airline
youcompleteme
vundle - manager of plugins
gundo - whatch history   
bufexplorer
		" <F1> : toggle this help
		" <enter> or o or Mouse-Double-Click : open buffer under cursor
		" <shift-enter> or t : open buffer in another tab
		" B : toggle if to save/use recent tab or not
		" d : delete buffer
		" D : wipe buffer
		" f : toggle find active buffer
		" p : toggle spliting of file and path name
		" q : quit
		" r : reverse sort
		" R : toggle showing relative or full paths
		" s : cycle thru "sort by" fields ['number', 'name', 'fullpath', 'mru', 'extension']
		" S : reverse cycle thru "sort by" fields
		" T : toggle if to show only buffers for this tab or not
		" u : toggle showing unlisted buffers

=diff=vimdiff
vimdiff -o [file1] [file2] ... diff files
diff -o [file1] [file2] > [file3] 



dbext 
h dbext-tutorial
vdbi-vim

command line
\t - autocomplete or next possibility
CTRL+N - next possibility
CTRL+P - previous possibility
edit .
write . 
---------------------

offsets
/default/2 - This command searches for the pattern "default" and then moves to the
beginning of the second line past the pattern.
/default/e - the 'e' offset indicates an offset from the end of the match.
/default/e+1 - adding a number moves forward
/default/b+2 - 'b' - moving to begining of word
+ positive number moves - negative number moves
Matching multiple times
/a* - matches a,aa,aaa, etc, but also the empty string beacuse zero times is included
/\(ab\)* - gruped 
/^ab\{3,4}$ - '$' after \{3,4}
pattern		match count ~
\{,4}		0, 1, 2, 3 or 4
\{3,}		3, 4, 5, etc.
\{0,1}		0 or 1, same as \=
\{0,}		0 or more, same as *
\{1,}		1 or more, same as \+
\{3}		3

also can {-1,3} - matching as little as possible
/a.\{-}b - example find ab,abb,abbb,abbbb and more
/a.*b - same as upper example
To match the "-" character itself make it the first or last one in the range.

\e	<Esc>
\t	<Tab>
\r	<CR>
\b	<BS>

There are a few more special cases for [] ranges, see |/[]| for the whole

item	matches			equivalent ~
\d	digit			[0-9]
\D	non-digit		[^0-9]
\x	hex digit		[0-9a-fA-F]
\X	non-hex digit		[^0-9a-fA-F]
\s	white space		[ 	]     (<Tab> and <Space>)
\S	non-white characters	[^ 	]     (not <Tab> and <Space>)
\l	lowercase alpha		[a-z]
\L	non-lowercase alpha	[^a-z]
\u	uppercase alpha		[A-Z]
\U	non-uppercase alpha	[^A-Z]

---
"many text"
"many text and 123123123"
'many text'
'many text and 123123123123'
/\('\|"\)[^\('\|"\)]*\('\|"\)

/\('\|"\) - first double quote
[^\('\|"\)]* - pass any double quote
\('\|"\) - last double quote
/"[^"]*"
<
"	  a double quote
[^"]	  any character that is not a double quote
*	  as many as possible
"  a double quote again


?(0or1) - in vim not work

gU - uppercase



=regexp
bre - basic regualr expression (posix standart)
ere - exstended regualr expression (posix standart)
sed not support 'ere'
gawk support 'ere'
	{m,n} - by default not support in gawk --re-interval

\([a-zA-Z]\|[а-яА-Я]{1,}\)

---
global change
=s
s - substitute (использовать вместо чего-л.)
n - search only?
g- global in line
:g! - applies the command to lines that DON`T match!
c - confirm each substitutio
:'s' - allow 'g' in end of sentence
:'50','100' - set which string apply change
:'1',$s/old/new/g - change all file

:%s/old/new/g - change all file!
:%s/old/new/gc - ask for confirm
:s/word/word77/ - change in string 'word' to 'word77'
:s/word/word99/g - change in all string 'word' to 'word99'
:-10,+33s/<pattern>/<replacement> - from 10 lines above the cursor to 33 lines below it
:-10;+3s//<pattern>/<replacement> - from 10 lines above the cursor for the following 33 lines
:.,$s/<pattern>/<replacement>
changes, related from context
:/<body>/,/<\/body>/s/<I>/<EM>/ - change all 'I' to 'EM' from 'body'
:?foo?+1,$-10s/<pattern>/<replacement>
=global
:g / ./ :.;/^$/join - join every 'paragraph' in a file into a single line
:g / ./ :.;/^$/-1join - or to leave the empty lines between them

:g/^$/d - delete all empty string
:g/pattern/s/old/new/g
or
:g/pattern/s//new/g

:g//t$ - copy all hightlight string in end file
:g//d$ - detete all hightlight string
:g!//d$ - detete all no hightlight string
:g/^$/d - delete all empty line
:g/^[ 	]*$/d - delete all empty line and line witch contain tab [\s\tab]

/\vword|word1 - search word|word1 in text
/.*Java\&.*line - find line containing 'Java' and 'line'


\< - start of the word
\> - end of the word
example - \<word\>
\d\{3} - {3} must be slashed

---

=r  Copy between files
		  :r ~/path/to/file - copy all file
		  :[n]r ~/path/to/file - copy all file start [n] lines
		  :[$ or 0]r ~/path/to/file - copy all file start/end [n] lines


		  :/pattern/r ~/path/to/file - copy to after pattern
		  ---
		  Cut or copy lines without counting the lines
		  1 In normal mode, go to the beginning of the section that you wath to yank.
		  2 Type mk to mark this spot as k.
		  3 Go to the end of the section you want to yank using whatever movement commands you like.
		  4 Type y'k (<y-yank>,<single quote-go to the mark>, k) To yank from the mark to the current location.
		  5 You can paste those lines wherever you want with p.

		  similarly, d'k will cut/delete the lines from the current location to the mark.
		  ---


---


window resizing
:resize -50 (50 - count of string) 
:vertical resize [N] - resize window verticale
 :10 new - new split in 10 size

 fold of the lines

 zf<motion>
 [N]zF

 zo - open up a flden line
 zc - close a fold again
 zn - unfold everything
 zi - toggle all folds
 zd - delete a fold
 ze - eliminate all folds

Nested folds
zm - increase the fold level (one level more foldy)
zM - maximize the foldedness
zr - reduce foldedness
zR - minimmize all foldedness


---
search
# - word under cursor
* - word under curso
g# - part of word
g* - part of word
read more about - vimgrep
- :marks
---

===============================================================================
---
=seaching
/up-down - view history search
/[letter]up-down - view history search
/\<word\> - find whole word
03.10 - using marks - stop here


---
search
# - word under cursor
* - word under curso
g# - part of word
g* - part of word
read more about - vimgrep
- :marks
---
===============================================================================
=vim.editing
===============================================================================
a - append after cursor
A - append after current line
i - insert before cursor
r - replace at cursor
~ - transpose case of text at cursor
R - replace from cursor to end of new text 
o - open new line after cursor
O - open new line before cursor
u - undo last action
ctrl+R - redo last action
U - undo current line
yy - copy current line
[n]yy - copy [n] lines from current line
y/string/ - copy from the cursor position to the string`s position searching forward
y?/string/ - copy from the string`s position to the curosr, seachingbackward
p - paste
ddp - cut and paste current line
:3,5d - delete 3,5 lines
dd - delete current line
dw - delete current word
d$ - delete from cursor to end of line
D - delete from cursor to end of line
cc - change current line
cw change current word
c$ - change from cursor to end of line
C - change from cursor to end of line
s - change current symbol
S - change current line
% - move to {[( 123 )]}
.test {
123
}


		>> - move text
		<< - move text
		K - go to man word of under cursor
		===V===
		CTRL+cv - insert blocks!!!
		ya_ - copy the entire '{/[/(/</"/'/`'
			v_U - make hightlighted area uppercase
			v->:sort - sort list! 
			v - in need go to star or end text push 'o'
			CTRL+V
			<CTRL+V>{motion}I{text} - Insert {text} before block on every line

			<CTRL+V>{motion}A{text} - Appends {text} after block on every line

			<CTRL+V>{motion}c{text} - Change every line of block to {text}

			<CTRL+V>{motion}R{text} - Change every character of block to {char}
			j - join line

			Cursor movement
			j - join line

			Cursor movement

			h/j/k/l - move left/down/up/right
			w - move forward word-by-word
			b - move backward word-by-word
			e - move to end of current word
			W - same as w but only uses space as delimiter
			B - same as b but only uses space as delimiter
			E - same as e but only uses space as delimiter
		} - move forward one paragraph
{ - move backward one paragraph
	) - move forward one line
		( - move backward one line
		  ^ - first non-blank character
		  0 - start of current line
		  $ - end of current line
		  gg - top of the file
		  G - bottom of the file
		  [n]gg - go to line [n]
		  nG - same as ngg
		  % - find match of current brace in the cursor
		  CTRL+] - jump in topic
		  CTRL+T - jump back
		  O(zero) - jump start line
		  <CR> - carriage return
		  CTRL+T - move \t (in insert mode)
		  CTRL+D - move back \t (in insert mode)
		  CTRL+W - delete word after cursor (in insert mode)
		  ---
		  Sessions
		  :mksession - to store a session
		  $ vim -S Session.vim - load a session
		  ---		
		  :mksession - to store a session

		  ---
		  Mastering Vim



		  CTRL+A [N]+1
		  CTRL+Y  - duplicate what in the same column on the preceding line
		  CTRL+E  - duplicate what in the same column on the preceding line
		  ---
		  marks
		  mx - mark position 'x'
		  ` - go to mark 'x'
		  ' - go to line 'x'
		  ---
		  :reg
		  ---
		  macros
		  :qregister - start record macros
		  q - end of record macros
		  @register - use macros	

		  ---
=




					source $VIM/path/to/file/*.vim start *.vim when vim start or put *.vim to plugin folder 
					all variable start operators
					let - 
					echo -
					call -

					see area:
					g - global
					v - global but use (predopredelena) vim
					s - local for script
					b - local for buffer
					w - local for window
					t - local for tab
					l - local for function
					a - arument for function


					PAPATH=$PATH:$HOME/bin - add a path
					echo echo Hello, World! > bin/hw - make a script
					chmod +x bin/hw - take a rights


					:marks
					ma - let :marks a	
					:deletemarks! - delete all marks
					'a - jump to line a
					`a - jump to position
					d'a - delete a
					`a - delete a
					c'a - change text from curent line 
					y`a - yank text to unnamed buffer from cursor to position of mark a
					:marks - list all the current marks
					:marks aB list marks a,B
					]' -jump to next line with a lowercase mark
					[' -jump to previous line with a lowercase makr
					]` -jump to next lowercase mark
					[` -jump to previous lowercase mark





=vmware
		gcc+ make apt-get install linux-headers-$(uname -r)
					linux-headers-generic
					0 vm install vmware tools
					0 mount cdrom '/dev/cdrom /mnt/cdrom
					2 cp from /media/..vmwaretools to another folder
					3 unzip
					4 run ./vmwaretool.pl
					5 see in mnt/hf../shader folders 
					6 not foget share folders in vmware!



=perl

type of variable and the.. use

$ - separate value number or string
@ - array
% - hash groupe value with string key
& - underprog
* - typeglob ( *[n] - all what have name *[n]	

${variable}
package 



cpan

===============================================================================
=dwb
===============================================================================
startpage
The default startpage. Possible values: an url or "about:blank" for an empty
startpage, default value: about:blank.
sync-files
Type of files to sync, see also file-sync-interval. Possible values are all, cookies,
history, session or a combination, default value: all.
enable-developer-extras
Whether the web-inspector should be enabled. Possible values: true/false, default
value: false.
[n]wi
Show the webinspector of tab n or of current tab if n is omitted. Note that
enable-developer-extras has to be set. (commmand web_inspector, aliases: inspect,
insp).

===============================================================================
=pc=old
===============================================================================
vga compatible controller intel corporation  82845g/gl[brookdale-g]/ge chipset
intergated graphics device -r03 asrock incorporation device 2562
radeon 9000 64vm ddr tvo




lspci - see what need driver

cat /var/log/Xorg.0.log | grep driver - see log

list installed drivers

aptitude search '~ixserver-xorg-video-'

list not installed 

aptitude search '!~ixserver-xorg-video-'
===============================================================================
=zsh.command=[command]
===============================================================================
man zshall
chsh -s /bin/
grml.org/zsh 

HISTFILE="$HOME/.zsh_history

HISTFILE="$HOME/.zhistory"
HISTSIZE=10000000
SAVEHIST=10000000
setopt BANG_HIST # Treat the '!' character specially during expansion.
setopt EXTENDED_HISTORY # Write the history file in the
":start:elapsed;command" format.
setopt INC_APPEND_HISTORY # Write to the history file immediately, not when the
shell exits.
setopt SHARE_HISTORY # Share history between all sessions.
setopt HIST_EXPIRE_DUPS_FIRST # Expire duplicate entries first when trimming
history.
setopt HIST_IGNORE_DUPS # Don't record an entry that was just recorded again.
setopt HIST_IGNORE_ALL_DUPS # Delete old recorded entry if new entry is a
duplicate.
setopt HIST_FIND_NO_DUPS # Do not display a line previously found.
setopt HIST_IGNORE_SPACE # Don't record an entry starting with a space.
setopt HIST_SAVE_NO_DUPS # Don't write duplicate entries in the history file.
setopt HIST_REDUCE_BLANKS # Remove superfluous blanks before recording entry.
setopt HIST_VERIFY # Don't execute immediately upon history expansion.
setopt HIST_BEEP # Beep when accessing nonexistent history.
===============================================================================
=debian=jessie=netinst
===============================================================================
debina netinst
instal with utilites (tasksel)
vmvare network
 device status
	[*]
	[*]
network connection
	bridged:
		[*]	
add to /etc/network/interfaces

auto eth0
iface eth0 inet dhcp

allow-hotplug eth0
=

instal

xserver-xorg
x-window-system
aptitude search '~ixserver-xorg-video'
aptitude search '!~xserver-xorg-video'

Xorg -configure
apt-cache stats
Xorg -config xorg.conf.new after copy file to /etc/X11/
make file in ~.xinitrc >> exec i3
startx

nix.zeya.org/wiki/базовая_настройка_xorg
==============================================================================
===============================================================================
=other
===============================================================================
=playonlinux
/usr/share/playonlinux/python/mainwindow.py
find string if(os.popen and match 3 string
/usr/share/playonlinux/lib/sources
find string if [ nad match 3 string
===============================================================================
===============================================================================
=hardware=hardinfo
===============================================================================
lshw
dmidecode
hardinfo
=df:   reports the amount of space used and available on currently mounted filesystems.
===============================================================================
===============================================================================
=system=xfce4
===============================================================================
xfce4 ++installsystem
xfce4-timer-plugin ++installsystem
xfce4-datetime-plugin ++installsystem
xfce4-xkb-plugin ++installsystem
xfce4-goodies ++installsystem
xfwm4 ++installsystem
xfce4-panel ++installsystem
xfce4-terminal ++installsystem
htop  ++installsystem
i3 ++installsystem
zsh ++installsystem
===
ranger ++installsystem
mc ++installsystem
xfe ++installsystem
=ranger ++installsystem
<c-h> - show hidden
<c-n> - new tab
<c-w> - close tab
<space> - mark files
<s-V> - toggle visual_mode
<F4> - edit file
===
tree ++installsystem
locate ++installsystem
file ++installsystem
hardinfo ++installsystem
vim ++installsystem
zathura ++installsystem
zathura-djvu ++installsystem
ttf-mscorefonts-installer ++installsystem
shutter ++installsystem
===
viewer candidate list
gpicview
mirage
qiv
xloadimage
graphicsmagic - cli
gthumb(gnome) ++installsystem
gwenview(kde)
===

freemind
kchmviewer
texstudio
anki ++installsystem
iceweasel
audacious

gcc ++installsystem
make ++installsystem
git ++installsystem
synaptic ++installsystem
smarty3
virtualbox
system-config-samba
===============================================================================
=xfce.hotkeys
===============================================================================
alt-f6 stack window
alt-f9 hide window
ctrl+alt+[home|end] move next|previous window
ctrl+alt+D show desktop
ctrl+alt+arrows[left][right] move between windows

===============================================================================
=games
===============================================================================
bsdgames

===============================================================================
=xmonad
===============================================================================
mod-space - swith window
mod-h|j
mod-[1-3] - n win
mod-shift-[n] - move to [n] win
===============================================================================
=ukraine.com.ua - reserved code access
5o4ms57 kg3s360n 7tbt465z np4do154
o0fg6z78 7yx33ss6 pk7732sh 55stt45x
88jzcm98 037did0j a331sbh0 h0o758hv 

sql 
user alfacap_abc
pwd cj3p6b2h

ip site 185.68.16.101
Админка сайта: http://ab-c.com.ua/wp-login.php
логин:buysite
пароль:cfvsqkexibqgfhjkm2 


===============================================================================
=select
===============================================================================-
=linksoriginalam.net - see smp4
===============================================================================
===============================================================================
=history
===============================================================================
hisotry | more
history | tail -[n]
![command] -execute prefious command with a specific word

===============================================================================
===============================================================================
=offtop
===============================================================================

Ибо не понимаю, что делаю: потому что не то делаю, что хочу, а что ненавижу, то делаю.

A wise old owl lived in an oak
The more he saw the less he spoke
The less he spoke the more he heard.
Why can't we all be like that wise old bird? 
===
Уж лучше быть, чем только слыть дурным,
Упрекам подвергаться понапрасную.
===============================================================================
===============================================================================
=links
===============================================================================
===============================================================================
===============================================================================
=sourceslist
===============================================================================
https://wiki.debian.org/ru/SourcesList

#official#wheezy
deb http://http.debian.net/debian wheezy main contrib non-free
deb-src http://http.debian.net/debian wheezy main contrib non-free

deb http://http.debian.net/debian wheezy-updates main contrib non-free
deb-src http://http.debian.net/debian wheezy-updates main contrib non-free

deb http://security.debian.org/ wheezy/updates main contrib non-free
deb-src http://security.debian.org/ wheezy/updates main contrib non-free

#official#squeeze
deb http://ftp.ua.debian.org/debian/ squeeze main non-free contrib
deb-src http://ftp.ua.debian.org/debian/ squeeze main non-free contrib
deb http://ftp.ru.debian.org/debian/ squeeze main non-free contrib
deb-src http://ftp.ru.debian.org/debian/ squeeze main non-free contrib
#backports
deb http://http.debian.net/debian wheezy-backports main 


#deb-multimedia
aptitude -t squeeze-backports install "package"
deb http://debian.nsu.ru/debian-marillat/ stable main

deb http://mirror.yandex.ru/debian-multimedia/ stable main
deb-src http://mirror.yandex.ru/debian-multimedia/ stable main

deb http://mirror.mephi.ru/debian-multimedia/ stable main
deb-src http://mirror.mephi.ru/debian-multimedia/ stable main

deb ftp://mirror.mephi.ru/debian-multimedia/ stable main
deb-src ftp://mirror.mephi.ru/debian-multimedia/ stable main 
===============================================================================
=windows=diskpart
===============================================================================
#diskpart
diskpart
list disk
select disk [n]
clean
create partition primary
select partition 1
active
format fs=[NTFS|FAT32]QUICK
assign
exit
#copy files to disk drive

     artkozlov
	o.o
	\_/

===============================================================================
=no-problems=
===============================================================================
when reinstall system
	save config files
		vimrc
		zshrc
		hosts
		apache/siteses-avialiable
=========
@sublime
=========
c+p
c+r
c+s+p
c+;

plugins
devdoc
=========
@windows
=========
Windows Quake Style Console
