**st v0.85**

## dependencies
(if it does not build, you might need to install the `*-devel` packages also)

+ `libX11`
+ `libXft`
+ `fontconfig`
+ `harfbuzz`

## patches
(most of these patches are from Luke Smith's)

+ alpha
+ boxdraw
+ ligatures
+ scrollback
+ resize-font
+ font2
+ gruvbox
+ xresources
+ bold is not bright

## install
to install my st, type

```
git clone --depth 1 https://github.com/pinitik1906/st.git $HOME/stuffs/git/st
cd $HOME/stuffs/git/st
sudo make clean install
```
