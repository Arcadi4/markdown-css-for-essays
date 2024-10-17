<!-- css -->

<link rel="stylesheet" href="./main.min.css">

<!-- highlight.js -->

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/styles/default.min.css">
<script src="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/highlight.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/languages/go.min.js"></script>
<script>hljs.highlightAll();</script>

# Primary Title

Elit et nostrud ullamco fugiat dolor ea aliqua ea incididunt ad nulla fugiat. Eiusmod incididunt sit commodo incididunt minim fugiat voluptate minim commodo. Minim dolore esse commodo duis nisi. Nisi est magna Lorem irure tempor proident quis mollit. Do nostrud consequat ut pariatur eu consectetur veniam elit velit pariatur nisi irure pariatur esse. In dolore et cillum cupidatat proident. Anim et non adipisicing ea.

Minim incididunt amet veniam elit commodo sit proident magna consequat labore ad occaecat consequat duis. Ullamco exercitation do est incididunt culpa qui fugiat anim id et. Aliquip labore et cupidatat laborum aliquip dolore deserunt. Excepteur officia anim et ipsum. Eu officia amet do irure.

## Secondary Title

Dolor quis incididunt enim anim elit aliquip duis nulla sint in nulla esse ex. Occaecat aliquip veniam mollit. Ut velit cupidatat amet eu esse proident ex velit do amet fugiat. Cillum culpa id tempor qui qui. Aliqua pariatur qui irure. Labore anim sit cillum esse nulla ad exercitation et. Nulla adipisicing laboris tempor occaecat qui sint ipsum aliquip.

### Lists

Culpa nisi duis velit sit magna magna in irure.

-   Adipisicing anim eiusmod eu minim aute ex est officia nisi culpa quis esse ea proident.
-   Voluptate aliqua aliqua id voluptate proident reprehenderit consequat in sint commodo Lorem dolor.
    -   Veniam ex reprehenderit veniam.
    -   Sunt Lorem irure esse mollit.
-   In dolore anim aute eu deserunt pariatur ad culpa adipisicing incididunt amet sint adipisicing ea.
-   Officia non exercitation do exercitation magna et cillum tempor laborum duis laborum est veniam aliqua eiusmod.

Irure id eiusmod laboris mollit ad sunt pariatur nulla. Id nulla ea velit.

1. Ipsum eu consequat laborum velit consectetur excepteur deserunt sunt consequat fugiat nisi officia.
2. In quis excepteur aliqua.
3. Nulla dolore et ea duis cillum.
4. Labore incididunt dolor enim voluptate nisi consectetur ad ipsum.

Reprehenderit nulla labore sit ipsum ex minim minim cillum elit non ipsum ad in in culpa. Nisi quis ea pariatur Lorem consectetur laborum aliquip ea mollit aute.

-   [ ] Nulla deserunt esse quis aute magna ea pariatur enim sunt aliquip sit irure.
-   [x] Sunt commodo laborum anim id reprehenderit adipisicing.
-   [ ] Incididunt ex laborum in id officia consequat nisi.

### Hyperlinks

Magna [culpa sit occaecat](example.com) dolore dolor. Laborum non [incididunt consequat](google.com) sunt ipsum fugiat esse exercitation ullamco consequat aliquip. Ea labore consectetur velit exercitation velit fugiat reprehenderit irure aliqua id voluptate sit do. Velit aute [dolore laborum](github.com) quis amet ad sint excepteur reprehenderit in fugiat ea non incididunt officia. Est aliqua reprehenderit non excepteur fugiat velit id labore non id nulla adipisicing.

## Code Block

Quis `occaecat non` qui ad culpa id voluptate. Consequat nulla ad `officia` exercitation cupidatat consequat eiusmod do ipsum nisi sit magna. Ea excepteur `aute` ipsum. Magna anim magna non adipisicing `elit` pariatur cupidatat. Velit aliquip enim nisi adipisicing.

```c
float Q_rsqrt( float number )
{
    long i;
    float x2, y;
    const float threehalfs = 1.5F;

    x2 = number * 0.5F;
    y  = number;
    i  = * ( long * ) &y;      // evil floating point bit level hacking
    i  = 0x5f3759df - ( i >> 1 );               // what the fuck?
    y  = * ( float * ) &i;
    y  = y * ( threehalfs - ( x2 * y * y ) );   // 1st iteration
    // y  = y * ( threehalfs - ( x2 * y * y ) );   // 2nd iteration, this can be removed

    return y;
}
```

## Equations

Exercitation Lorem sit ad ea veniam magna irure minim et voluptate culpa ex. Fugiat ad sint nulla pariatur duis sunt. Sint pariatur officia veniam anim veniam qui dolor Lorem ex qui ipsum laboris ex ipsum quis. Do qui labore labore ea consequat excepteur fugiat amet esse aute consectetur fugiat deserunt veniam. Minim pariatur sint officia irure consectetur culpa qui. Eu ex laboris consequat laborum sint. Culpa quis minim sint.

$$
\mathcal{F}\{f(t)\} = F(\omega) = \int_{-\infty}^{\infty} f(t) e^{-j\omega t} dt
$$

## Tables

WIP

| Header 1 | Header 2 | Header 3 |
| -------- | -------- | -------- |
| Row 1    | Data 1   | Data 2   |
| Row 2    | Data 3   | Data 4   |
| Row 3    | Data 5   | Data 6   |

## Images

WIP

Velit eiusmod ex excepteur sit do exercitation nulla. Ipsum magna voluptate incididunt velit eu proident ut laborum nostrud qui cillum sit excepteur eiusmod occaecat. Do nulla incididunt cupidatat deserunt fugiat do. Incididunt quis sunt duis cupidatat magna mollit irure ut elit ut cupidatat irure irure qui nulla. Ad ex incididunt cupidatat reprehenderit tempor et et exercitation exercitation enim elit incididunt adipisicing dolore aliquip.

![vortex](https://unsplash.com/photos/DvwKzaY6Xm8/download?ixid=M3wxMjA3fDB8MXxhbGx8fHx8fHx8fHwxNzI5MTc2NTE5fA&force=true)

Photo by [Li Zhang](https://unsplash.com/@sunx?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash") on [Unsplash](https://unsplash.com/photos/a-blue-abstract-background-with-wavy-lines-DvwKzaY6Xm8?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash)

## Footnotes

WIP

Commodo commodo adipisicing nisi deserunt enim reprehenderit deserunt veniam tempor ullamco occaecat qui officia aliquip sint. Sint elit est sit qui. Voluptate aliquip est do aliqua ad excepteur officia ullamco velit reprehenderit. Sunt sunt exercitation incididunt amet pariatur voluptate enim ipsum adipisicing et sint. Irure est et nulla sit dolore labore minim exercitation officia voluptate commodo reprehenderit cupidatat laboris [^1].

[^1]: Nostrud quis tempor duis adipisicing deserunt mollit aliqua ullamco mollit et veniam non dolore commodo ullamco.
