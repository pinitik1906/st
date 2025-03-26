**st v0.92**

## dependencies
(if it does not build, you might need to install the `*-devel` packages also)

+ `libX11`
+ `libXft`
+ `fontconfig`
+ `freetype`
+ `pkg-config`

## patches

+ bold is not bright
+ boxdraw
+ clipboard
+ dynamic cursor color
+ font2
+ gruvbox-dark
+ nano shortcuts support
+ nobadweight
+ scrollback w/ mouse
+ workingdir

## install
to install my st, type

```
git clone --depth 1 https://github.com/pinitik1906/st.git $HOME/stuffs/git/st
cd $HOME/stuffs/git/st
sudo make clean install
```

## configure
to edit my st build, please only configure in `config.h`
