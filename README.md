# Css Effects

You can find all buttons and images animations components in [/src/components/](https://github.com/uniboxx/astro-components-buttons/tree/main/src/components).

How to use buttons:

```astro
<Buttonxx>some_text</Buttonxx>
```

How to use image animations:

```astro
---
import { Image } from 'astro:assets';
import image from '/link_to_image'
---
<Animationxx width={xxx} height={xxx}>
  <Image src={image} alt='some text' loading={lazy/eager}>
  <!-- every element below is optional -->
  <figcaption slot='caption'>
    <h2>some_text</h2>
    <p>some_text</p>
  <!-- from animation07 you can add a link -->
    <a href='#'>some_text</a>
  </figcaption>
</Animationxx>

<!-- only for animation12 -->
<Animationxx image={image} width={xxx} height={xxx}>
<!-- no Image component and optionally the figcaption element like before -->
```

Hot to use links:

```astro
<Linkxx>some_text</Linkxx>
```
