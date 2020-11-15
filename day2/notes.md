# Day 2 - EM & REM units

Content: https://courses.kevinpowell.co/courses/conquering-responsive-layouts/349964-day-2-getting-familiar-with-relative-units

## Notes

* `rem` is relative to the font-size of the root element of the page, which is the `html` element, which equates to 16px in most browser but can change due to user settings of their browser.
* `em` is relative to the font-size of the parent element
* `em` can compound if elements that are using it are nested, like a list that contains sublists. Because a nested `li` font size set in `em` will be relative to the `em` font-size set of its parent and so on and so fort. Better watch out.
* For font-size `rem` are recommended over `em` because of the compounding problem mentioned above 
* When `em` is used in non `font-size` properties they are relative to the element's font-size and not to the element's parent's font-size.
* `em` are great for scaling margins, widths, padding etc based on the font-size of the element, so proportions are kept. 💯
