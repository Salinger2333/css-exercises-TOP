# A Basic Header

Use flexbox rules to create this very common webpage header style. The benefit to using flex here is that everything should be _flexible_. Check out the two screenshots below to get an idea of how it should scale with your screen. Besides flex rules, you'll also want to add some rules for margin and padding. (Hint: `ul`s have some default margin/padding that you will need to deal with.)
使用弹性盒子（Flexbox）规则来创建这种非常常见的网页头部样式。在这里使用弹性盒子的好处在于，所有元素都应该是**灵活可变的**。查看下面的两张截图，了解它应该如何随屏幕大小进行缩放。除了弹性盒子规则之外，你还需要添加一些关于外边距（margin）和内边距（padding）的规则。（提示：无序列表 `<ul>` 有一些默认的外边距和内边距，你需要对其进行处理。）
## Desired Outcome

narrow:
![narrow](./desired-outcome-narrow.png)

wide: 
![wide](./desired-outcome-wide.png)

### Self Check
- There is space between all items and the edge of the header (specific px amount doesn't matter here).
- Logo is centered vertically and horizontally.
- list-items are horizontal, and are centered vertically inside the header.
- left-links and right-links are pushed all the way to the left and right, and stay at the edge of the header when the page is resized.
- Your solution does not use floats, inline-block, or absolute positioning.

- Note: For this exercise, it's completely acceptable to not match the font-family.