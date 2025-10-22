`position: sticky` 通常用于导航栏或元素，当用户向下滚动页面时，你希望它们保持可见，但当向上滚动时，它们会返回到正常位置。

当元素设置为 `position: sticky` 时，其最初的行为类似于 `position:relative`。

这意味着该元素将出现在文档中的正常位置。

当到达指定的滚动点时，元素将切换到固定位置（就像设置为 `position: fixed`）并且不会随其余内容滚动。

下面是一个例子：

## --- code ---

language: css
filename:
line_numbers: true
line_number_start: 1
line_highlights:
-----------------------------------------------------

.sticky-element {
position: sticky;
top: 50px;
}

\--- /code ---

第 2 行将具有属性 `class="sticky-element"` 的任何元素的position属性设置为 `sticky`。

第 3 行设置元素为“粘性”（其位置固定）的视口顶部距离。