---
templateKey: blog-post
path: blog
title: Hello Netlify CMS
date: 2017-12-30T07:48:19.317Z
description: Nothing more than a test!
---
I am going to try Netlify CMS and see if it supports RTL languages. I know it won't support them completely but at least the basics. From there we will decide how to contribute to this project. May be we will create a separate one based on what exists now. Or contribute directly to the official one.

مرحبا أهلا وسهلا،

جميل جدا، الظاهر أن محرر النصوص يدعم النصوص العربية. ولكن المعاين لا يدعمها بشكل جيد.

Ok, seems like the editor support RTL in a good way. But the previewer has some issues with aligning the texts. Now, we will test it with mixed contents and how it will be behave.

Hello mate, مرحبا صاح

مرحبا صاح، Hello mate

Same thing with the mixed content. The editor support it very well but the previewer has everything aligned to the left.

I think this is due to the components being used here. So this is the point to start with. We will try to fix the previewer first to let some of our projects start. Then, we will add layout direction or order switcher. Which will be like button to switch between RTL and LTR editing view. This way the editor will be on the right for RTL languages. 

About the previewer, I don't know if the previewer uses the same templates provided by the published post theme or static site generator. Or it uses a custom one only to preview the content. But in any case the alignment must be fixed to get the best picture possible. Draft.js has a good support for RTL/LTR and mixed content, so we will try to use theirs. Or create our custom editor component using the Draft.js library. Which is good, because of the available plugins and it's support of extending whilst remaining consistent.
