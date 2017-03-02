# ArchLinuxJP Images

ArchLinuxJP用に作成したアイコンやArchLinux関連の画像リンクなどを掲載します。

## ArchLinuxJP

![](https://raw.githubusercontent.com/archlinuxjp/arch-image/master/logo/archlinux-logo-honeycomb_512x512.png)

## ArchLinux

![](https://raw.githubusercontent.com/archlinuxjp/arch-image/master/logo/archlinux-logo-default_512x512.png)

![](https://raw.githubusercontent.com/archlinuxjp/arch-image/master/logo/archlinux-logo-normal_512x512.png)

```bash
$ sudo pacman -S imagemagick
$ convert -resize 120x120 input.png output.png
```

## ArchLinux関連の画像リンク

## IconFinder

[https://www.iconfinder.com](https://www.iconfinder.com/search/?q=archlinux)

`IconFinder`は、豊富な種類のアイコンが公開されているサイトです。

## IcoMoon

[https://icomoon.io](https://icomoon.io/app/#/select)

`IcoMoon`は、オリジナルのWebフォントを作成できます。

アイコンフォントのメリットは、CSSによるエフェクトが追加できる点などです。例えば、マウスオーバーでアイコンを光らせることも可能。

したがって、例えば、Webサイトの顔となるようなアイコン部分は、Webフォントで作成する方が良いとされています。

> ./font/icomoon/demo.html

```html
<span class="icon-archlinux"></span>
```

```css
.icon-archlinux:before {
    content: "\e900";
}
```

```html
<p> &#xe900; ArchLinux </p>
```

## SVG to PNG

```bash
$ sudo pacman -S imagemagick --noconfirm
$ convert -geometry 190x40! archlogo.svg archlogo.png
or
$ sudo pacman -S inkscape --noconfirm
$ inkscape -z arch.svg -e arch.png
```

## PNG to SVG

PNGをSVGに変換するには、ImageMagickなどでは難しいので、InkscapeをインストールしてPNGファイルを読み込み、SVGで保存します。

```bash
$ inkscape -f arch.png -l arch.svg
```

## FontAwesome to PNG

https://github.com/odyniec/font-awesome-to-png

```bash
$ sudo pip install pillow
```

