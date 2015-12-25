# ArchLinuxJP Images

ArchLinuJP用に作成したアイコンやArchLinux関連の画像リンクなどを掲載します。

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

## FontAwesome

[http://fortawesome.github.io](http://fortawesome.github.io/Font-Awesome/icon/linux/)

`FontAwesome`は、Webフォント業界では、最も有名なサイトです。[BootStrap](http://getbootstrap.com/)などと合わせてよく使われているのを見かけます。

残念ながら、Linuxのものは用意されているものの、ArchLinuxのものはありません。その場合、先ほど挙げた`IcoMoon`で自作することになります。

