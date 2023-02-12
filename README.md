<html>
<head></head>
<body>
<h1>Final Rice</h1>
<img src="./Resources/Final Images/screenshot-20230211-162109Z-all.png">
<img src="./Resources/Final Images/screenshot-20230211-162028Z-all.png">
<img src="./Resources/Final Images/screenshot-20230211-161852Z-all.png">
<img src="./Resources/Final Images/screenshot-20230211-162216Z-all.png">

<p><h2><Resources></h2>
<h3>Themes</h3>
I am using <a href="https://www.gnome-look.org/p/1099856">Ant Themes</a> <strong> Ant-Nebula.tar.xz </strong> Theme.
<br>
<h3>Icons</h3>
I am using <a href="https://www.gnome-look.org/p/1340791/">Reversal icon themes</a> <strong> Reversal.tar.xz </strong>icon pack.</p>
<p><h3>Shell</h3>
I am using <code>alacritty</code> with <code>fish</code>.</p>
<p></h3>Font<h3>
I am using <a href="https://github.com/FortAwesome/Font-Awesome/releases/tag/v4.7.0"> Font-Awesome 4.7.0 </a>.Download the source file,unzip it and copy the <code> ttf </code> fonts inside the fonts file to your pc's font directory.  </p>
<p><h3>Polybar</h3>
For building <abbr title="The bar you see above">polybar</abbr> your will first need to install <code>yay</code>.<br>
<code>cd ~
mkdir -p /tmp/yay_install
cd /tmp/yay_install

sudo pacman -S base-devel

sudo pacman -S expac yajl git

git clone https://aur.archlinux.org/yay.git 
cd yay
makepkg -si 

cd ~ 
rm -rf /tmp/yay_install
</code>

After that you can build polybar by <br>
<code>sudo pacman -S cairo libxcb python2 xcb-proto xcb-util-image xcb-util-wm xcb-util-xrm jsoncpp
yay -S polybar-git 
</code>

Setting up the wallpaper
Create a Pictures Directory and inside of that create a Wal directory.<>br
<code>cd ~
mkdir Pictures
cd Pictures
mkdir Wal
</code>
now paste the wallpaper from Resources into this directory.
</p>
</body>
</html>
