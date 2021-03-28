css选择器


x{
}直接选择含有x标签的元素
#x{
}选择对应id=x的元素
.x{
}选择含有class=x的所有元素。
a.x{
}选则含有class=x属性的a类标签的所有元素
*{
}选择所有元素
a,b,c{
}选择a,b,c元素
a>b{
}选择所有a的标签的子代标签中所有的b标签元素
.a.b{
}选择同时含有class a和b的元素
.a .b{
}选择所有a的类的后代(子代及以后)标签中所有的b类元素
a b{
}选择所有a的标签的后代((子代及以后))中所有的b标签元素
a+b{
}选择紧接a元素后面的b元素(第一个)
a~b{
}选择前面含有a元素的b元素
后续转自w3school  红色代表出现频率较高的用法

| [[_attribute_]](https://www.w3school.com.cn/cssref/selector_attribute.asp) | [target] | 选择带有 target 属性的所有元素。 |
| --- | --- | --- |
| [[_attribute_=_value_]](https://www.w3school.com.cn/cssref/selector_attribute_value.asp) | [target=_blank] | 选择带有 target="_blank" 属性的所有元素。 |
| [[_attribute_~=_value_]](https://www.w3school.com.cn/cssref/selector_attribute_value_contain.asp) | [title~=flower] | 选择 title 属性包含单词 "flower" 的所有元素。 |
| [[_attribute_|=_value_]](https://www.w3school.com.cn/cssref/selector_attribute_value_start.asp) | [lang&#124;=en] | 选择 lang 属性值以 "en" 开头的所有元素。 |
| [[_attribute_^=_value_]](https://www.w3school.com.cn/cssref/selector_attr_begin.asp) | a[href^="https"] | 选择其 src 属性值以 "https" 开头的每个 <a> 元素。 |
| [[_attribute_$=_value_]](https://www.w3school.com.cn/cssref/selector_attr_end.asp) | a[href$=".pdf"] | 选择其 src 属性以 ".pdf" 结尾的所有 <a> 元素。 |
| [[_attribute_*=_value_]](https://www.w3school.com.cn/cssref/selector_attr_contain.asp) | a[href*="w3schools"] | 选择其 href 属性值中包含 "abc" 子串的每个 <a> 元素。 |
| [:active](https://www.w3school.com.cn/cssref/selector_active.asp) | a:active | 选择活动链接。 |
| [::after](https://www.w3school.com.cn/cssref/selector_after.asp) | p::after | 在每个 <p> 的内容之后插入内容。 |
| [::before](https://www.w3school.com.cn/cssref/selector_before.asp) | p::before | 在每个 <p> 的内容之前插入内容。 |
| [:checked](https://www.w3school.com.cn/cssref/selector_checked.asp) | input:checked | 选择每个被选中的 <input> 元素。 |
| [:default](https://www.w3school.com.cn/cssref/selector_default.asp) | input:default | 选择默认的 <input> 元素。 |
| [:disabled](https://www.w3school.com.cn/cssref/selector_disabled.asp) | input:disabled | 选择每个被禁用的 <input> 元素。 |
| [:empty](https://www.w3school.com.cn/cssref/selector_empty.asp) | p:empty | 选择没有子元素的每个 <p> 元素（包括文本节点）。 |
| [:enabled](https://www.w3school.com.cn/cssref/selector_enabled.asp) | input:enabled | 选择每个启用的 <input> 元素。 |
| [:first-child](https://www.w3school.com.cn/cssref/selector_first-child.asp) | p:first-child | 选择属于父元素的第一个子元素的每个 <p> 元素。 |
| [::first-letter](https://www.w3school.com.cn/cssref/selector_first-letter.asp) | p::first-letter | 选择每个 <p> 元素的首字母。 |
| [::first-line](https://www.w3school.com.cn/cssref/selector_first-line.asp) | p::first-line | 选择每个 <p> 元素的首行。 |
| [:first-of-type](https://www.w3school.com.cn/cssref/selector_first-of-type.asp) | p:first-of-type | 选择属于其父元素的首个 <p> 元素的每个 <p> 元素。 |
| [:focus](https://www.w3school.com.cn/cssref/selector_focus.asp) | input:focus | 选择获得焦点的 input 元素。 |
| [:fullscreen](https://www.w3school.com.cn/cssref/selector_fullscreen.asp) | :fullscreen | 选择处于全屏模式的元素。 |
| [:hover](https://www.w3school.com.cn/cssref/selector_hover.asp) | a:hover | 选择鼠标指针位于其上的链接。 |
| [:in-range](https://www.w3school.com.cn/cssref/selector_in-range.asp) | input:in-range | 选择其值在指定范围内的 input 元素。 |
| [:indeterminate](https://www.w3school.com.cn/cssref/selector_indeterminate.asp) | input:indeterminate | 选择处于不确定状态的 input 元素。 |
| [:invalid](https://www.w3school.com.cn/cssref/selector_invalid.asp) | input:invalid | 选择具有无效值的所有 input 元素。 |
| [:lang(_language_)](https://www.w3school.com.cn/cssref/selector_lang.asp) | p:lang(it) | 选择 lang 属性等于 "it"（意大利）的每个 <p> 元素。 |
| [:last-child](https://www.w3school.com.cn/cssref/selector_last-child.asp) | p:last-child | 选择属于其父元素最后一个子元素每个 <p> 元素。 |
| [:last-of-type](https://www.w3school.com.cn/cssref/selector_last-of-type.asp) | p:last-of-type | 选择属于其父元素的最后 <p> 元素的每个 <p> 元素。 |
| [:link](https://www.w3school.com.cn/cssref/selector_link.asp) | a:link | 选择所有未访问过的链接。 |
| [:not(_selector_)](https://www.w3school.com.cn/cssref/selector_not.asp) | :not(p) | 选择非 <p> 元素的每个元素。 |
| [:nth-child(_n_)](https://www.w3school.com.cn/cssref/selector_nth-child.asp) | p:nth-child(2) | 选择属于其父元素的第二个子元素的每个 <p> 元素。 |
| [:nth-last-child(_n_)](https://www.w3school.com.cn/cssref/selector_nth-last-child.asp) | p:nth-last-child(2) | 同上，从最后一个子元素开始计数。 |
| [:nth-of-type(_n_)](https://www.w3school.com.cn/cssref/selector_nth-of-type.asp) | p:nth-of-type(2) | 选择属于其父元素第二个 <p> 元素的每个 <p> 元素。 |
| [:nth-last-of-type(_n_)](https://www.w3school.com.cn/cssref/selector_nth-last-of-type.asp) | p:nth-last-of-type(2) | 同上，但是从最后一个子元素开始计数。 |
| [:only-of-type](https://www.w3school.com.cn/cssref/selector_only-of-type.asp) | p:only-of-type | 选择属于其父元素唯一的 <p> 元素的每个 <p> 元素。 |
| [:only-child](https://www.w3school.com.cn/cssref/selector_only-child.asp) | p:only-child | 选择属于其父元素的唯一子元素的每个 <p> 元素。 |
| [:optional](https://www.w3school.com.cn/cssref/selector_optional.asp) | input:optional | 选择不带 "required" 属性的 input 元素。 |
| [:out-of-range](https://www.w3school.com.cn/cssref/selector_out-of-range.asp) | input:out-of-range | 选择值超出指定范围的 input 元素。 |
| [::placeholder](https://www.w3school.com.cn/cssref/selector_placeholder.asp) | input::placeholder | 选择已规定 "placeholder" 属性的 input 元素。 |
| [:read-only](https://www.w3school.com.cn/cssref/selector_read-only.asp) | input:read-only | 选择已规定 "readonly" 属性的 input 元素。 |
| [:read-write](https://www.w3school.com.cn/cssref/selector_read-write.asp) | input:read-write | 选择未规定 "readonly" 属性的 input 元素。 |
| [:required](https://www.w3school.com.cn/cssref/selector_required.asp) | input:required | 选择已规定 "required" 属性的 input 元素。 |
| [:root](https://www.w3school.com.cn/cssref/selector_root.asp) | :root | 选择文档的根元素。 |
| [::selection](https://www.w3school.com.cn/cssref/selector_selection.asp) | ::selection | 选择用户已选取的元素部分。 |
| [:target](https://www.w3school.com.cn/cssref/selector_target.asp) | #news:target | 选择当前活动的 #news 元素。 |
| [:valid](https://www.w3school.com.cn/cssref/selector_valid.asp) | input:valid | 选择带有有效值的所有 input 元素。 |
| [:visited](https://www.w3school.com.cn/cssref/selector_visited.asp) | a:visited | 选择所有已访问的链接。 |





style


颜色
background-color 背景色 
可以通过 #ff0000 二进制颜色 rgba()或者rgb()函数-rgba色彩 hsla()函数-hsla色彩  设置样式


**rgba(**_red,_** **_green_**, **_blue, alpha_**)  hsl(**_hue_**, **_saturation_**, **_lightness_**)**
_
_opacity设置透明度_
_
_设置背景图片_
background-image: url("图片路径")


设置重复规则
background-repeat: 

| repeat | 水平竖直都重复 |
| :--- | :--- |
| repeat-x | 仅x方向重复 |
| repeat-y | 仅y方向重复 |
| no-repeat | 不设置重复 |
| space | 尽量不发生裁剪的填充 |
| round | 无缝重复填充 |
| initial | 设置默认 |
| inherit | 规则继承自父元素 |



