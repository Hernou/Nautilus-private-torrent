Nautilus-private-torrent
---------
This add a button to right clic for easy create a torrent with the selected file

![](https://raw.githubusercontent.com/Hernou/Nautilus-private-torrent/master/Capture%20du%202014-07-16%2014:07:25.png)

there is a save for me, you can complete the public tracker list or translate it if you want ;-)

Dependencies :
------------
nautilus-actions ( http://www.nautilus-actions.org )

mktorrent ( http://mirror.aarnet.edu.au/debian/pool/main/m/mktorrent/ )
```html
sudo apt-get install nautilus-actions mktorrent
```
Install :
------------

```html
git clone https://github.com/Hernou/Nautilus-private-torrent.git && mkdir -p $HOME/.local/share/file-manager & mkdir -p $HOME/.local/share/file-manager/actions & sleep 7 && cp -rf ~/Nautilus-private-torrent/cf2bc7ce-3a0a-4870-8188-58a871116d18.desktop ~/.local/share/file-manager/actions/cf2bc7ce-3a0a-4870-8188-58a871116d18.desktop && rm -rf ~/Nautilus-private-torrent && nautilus -q 


```
