# Day 1 Notes

* Avoid setting hights or widths in elements because if the content is bigger than the container the content will overflow. If content overflows it will still be accessible but the browser will add scrollbars to allow accessing it. Depending on contrast of the overflowed content with it's background a user might not be able to see it but it will be there. 
* Be careful when setting `overflow: hidden' as content will be chopped off and invisible if it overflows.
* Padding is a good way to get more background area if what you want is things elements to appear bigger
* By default block level elements like `div`, `p` `h1` etc 100% wide of their parent.
* Percentage width on a child block element will always be relative to the width of its parent.
* The web is responsive by default we ruin it with CSS by setting hard widths or heights sometimes.
