## IchigoJam FONT .woff

![IchigoJam FONT](/ichigojam-font.jpg)

CDN: [jsDelivr](https://www.jsdelivr.com/)

- 日本語: [IchigoJam フォント TrueType | イチゴジャム レシピ](https://15jamrecipe.jimdofree.com/%E3%83%84%E3%83%BC%E3%83%AB/%E3%83%95%E3%82%A9%E3%83%B3%E3%83%88-truetype/)

___

## Example of using font

CSS:

```
@font-face
{
    font-family: "ichigojam";
    font-style: normal;
    font-weight: 400;
    src: local('IchigoJam-1.4'), local('IchigoJam-1.4-Regular'),
         url("https://cdn.jsdelivr.net/gh/fu-sen/ichigojam-font@20190814/IchigoJam-1.4.woff2") format('woff2'),
         url("https://cdn.jsdelivr.net/gh/fu-sen/ichigojam-font@20190814/IchigoJam-1.4.woff") format('woff'),
         url("https://cdn.jsdelivr.net/gh/fu-sen/ichigojam-font@20190814/IchigoJam-1.4.ttf") format('ttff');
}
code.language-ichigojam
{
    font-family: 'ichigojam';
    font-size: 16px;
    line-height: 18px;
    color: #ffffff;
    background-color: #000000;
    white-space: pre-wrap;
    word-break: break-all;
    padding: 15px;
}
```

If you want to use fonts in HTML:

```
<pre><code class="language-ichigojam">10 INPUT A
20 INPUT B
30 C=A+B
40 PRINT C
50 END
</code></pre>
```

or Markdown:

<pre><code>```ichigojam
10 INPUT A
20 INPUT B
30 C=A+B
40 PRINT C
50 END
```
</code></pre>

Output:

![Output IchigoJam FONT](/output.png)

Currently the latest is `IchigoJam BASIC 1.4` .\
`IchigoJam BASIC 1.2` font:\
change `1.4` to` 1.2`

Development version (It can change suddenly!):\
change `20190814-2` to `master` 

___

## What's IchigoJam?

![IchigoJam R](/ichigojam-r.jpg)\
![IchigoJam BASIC](/ichigojam-basic.jpg)

Details: [Kid's PC IchigoJam](https://ichigojam.net/index-en.html)

Do you have an old Raspberry Pi?\
Try: [IchigoJam BASIC RPi](https://na-s.jp/IJBRPi/)

Or you can use it now!
[IchigoJam web](https://fukuno.jig.jp/app/IchigoJam/)

___

## License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

[CC BY](http://creativecommons.org/licenses/by/4.0/) [IchigoJam](https://ichigojam.net/) / [🎈 BALLOON | FU-SEN](https://15jamrecipe.jimdofree.com/)

