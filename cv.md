<header class="header">

<div class="container">

<nav class="nav">

*   [profile](#profile)
*   [contact](#contact)
*   [summary](#summary)
*   [skills](#skills)
*   [code](#code)
*   [courses](#courses)
*   [projects](#projects)
*   [education](#education)
*   [languages](#languages)

</nav>

</div>

</header>

<main class="main">

<div class="container">

<section class="section" id="profile">

# Aleksandr Mikhaylov

![Avatar](./img/avatar.jpg)

Beginner/Future FE Developer

</section>

<section class="section" id="contact">

## contact

*   e-mail: [alex.mcgee.mail@gmail.com](mailto:alex.mcgee.mail@gmail.com)
*   telegram: [@ranpu](https://t.me/ranpu)

</section>

<section class="section" id="summary">

## summary

I'm a Beginner Front End Developer with ML Analytic experience.

</section>

<section class="section" id="skills">

## skills

*   HTML5, CSS3 - Beginner
*   JavaScript - Beginner
*   Python - Junior
*   Adobe Photoshop, CorelDraw
*   GitHub, Git
*   VS Code

</section>

<section class="section" id="code">

## code

[Count IP Addresses KATA from CODEWARS (JavaScript solution):](https://www.codewars.com/kata/526989a41034285187000de4/javascript)

<pre>                        `function ipsBetween(start, end){
    start = start.split('.')
    end = end.split('.')
    let diff = []

    for (let i = 0; i < 4; i++) {
        start[i] = Number(start[i])
        end[i] = Number(end[i])
        diff.push(start[i] - end[i])
    }

    return Math.abs((256**3 * diff[0]) + 
                    (256**2 * diff[1]) + 
                    (256 * diff[2]) + diff[3])
}` 
                    </pre>

[Range Extraction KATA from CODEWARS (Python solution):](https://www.codewars.com/kata/51ba717bb08c1cd60f00002f/python)

<pre>                        `def solution(args):
    args += [None]
    final, middle = [], [args[0]]

    for x in range(1, len(args)):
        if args[x-1] + 1 != args[x]:
            if len(middle) > 2:
                final += [str(middle[0]) + '-' + str(middle[-1])]
            else:
                final += [str(x) for x in middle]
            middle = [args[x]]
        else:
            middle += [args[x]]

    return ','.join(final)` 
                    </pre>

</section>

<section class="section" id="courses">

## courses

*   RSSchool Stage0 (In Progress)

</section>

<section class="section" id="projects">

## projects

*   [First CV](https://github.com/Ranpu/rsschool-cv/tree/gh-pages)

</section>

<section class="section" id="education">

## education

*   Art College №59, Moscow (2013)

</section>

<section class="section" id="languages">

## languages

*   Russian - Native
*   English - Intermediate/Upper-intermediate

</section>

</div>

</main>

<footer class="footer">

<div class="container">

*   [![GitHub Logo](./img/logo/github/GitHub-Mark-Light-32px.png)](https://github.com/Ranpu/) 
*   **©2022 by Aleksandr Mikhaylov**

*   [![RSSchool Logo](./img/logo/rsschool/rss-mark-light.svg)](https://rs.school/js-stage0/) 
</div>
</footer>