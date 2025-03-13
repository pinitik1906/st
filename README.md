**st v0.92**

## dependencies
(if it does not build, you might need to install the `*-devel` packages also)

+ `libX11`
+ `libXft`
+ `fontconfig`
+ `harfbuzz`

## patches

+ bold is not bright
+ boxdraw
+ clipboard
+ font2
+ gruvbox-dark
+ scrollback w/ mouse

## install
to install my st, type

```
git clone --depth 1 https://github.com/pinitik1906/st.git $HOME/stuffs/git/st
cd $HOME/stuffs/git/st
sudo make clean install
```
