# Not My Type

A simple page to check the accessibility ‘performance’ of a web font against another.

It was inspired by some local authors of a typeface[^1] and blog posts on inclusive typography[^2]. Making note of their research and examples, I wanted to jump into the static images and hot-swap them with real web fonts that I was exploring for projects.

The idea is you’ll come across a font that you think will work, but in the end find it just isn’t your type.

Demo - https://elliott-nmt.netlify.app/

[^1]: [Inclusive Sans](https://www.oliviaking.com/inclusivesans/feature)
[^2]: Typography in Inclusive Design - [Part one](https://www.visionaustralia.org/business-consulting/digital-access/blog/typography-in-inclusive-design-part-1), [part two](https://www.visionaustralia.org/business-consulting/digital-access/blog/typography-in-inclusive-design-part-2)

## Usage

Use the project page to prototype and check typeface candidates against some basic principles.

The page uses [Web Font Loader](https://github.com/typekit/webfontloader) for basic loading of fonts from the likes of [Google Fonts](https://github.com/typekit/webfontloader?tab=readme-ov-file#google) or [Adobe Fonts/Typekit](https://github.com/typekit/webfontloader?tab=readme-ov-file#typekit).

When the families are added, mention two to compare in the CSS variables, eg:

```css
:root {
      --font-base: Inclusive Sans;
      --font-one: Comic Sans MS;
      --font-two: Papyrus; /* “Whatever they did, IT WASN’T ENOUGH!” */
    }
```
