css选择器<br />
<br />x{<br />}直接选择含有x标签的元素<br />#x{<br />}选择对应id=x的元素<br />.x{<br />}选择含有class=x的所有元素。<br />a.x{<br />}选则含有class=x属性的a类标签的所有元素<br />*{<br />}选择所有元素<br />a,b,c{<br />}选择a,b,c元素<br />a>b{<br />}选择所有a的标签的子代标签中所有的b标签元素<br />.a.b{<br />}选择同时含有class a和b的元素<br />.a .b{<br />}选择所有a的类的后代(子代及以后)标签中所有的b类元素<br />a b{<br />}选择所有a的标签的后代((子代及以后))中所有的b标签元素<br />a+b{<br />}选择紧接a元素后面的b元素(第一个)<br />a~b{<br />}选择前面含有a元素的b元素<br />后续转自w3school  红色代表出现频率较高的用法

| [_attribute_] | [target] | 选择带有 target 属性的所有元素。 |
| --- | --- | --- |
| [_attribute_=_value_] | [target=_blank] | 选择带有 target="_blank" 属性的所有元素。 |
| [_attribute_~=_value_] | [title~=flower] | 选择 title 属性包含单词 "flower" 的所有元素。 |
| [_attribute_&#124;=_value_] | [lang&#124;=en] | 选择 lang 属性值以 "en" 开头的所有元素。 |
| [_attribute_^=_value_] | a[href^="https"] | 选择其 src 属性值以 "https" 开头的每个 <a> 元素。 |
| [_attribute_$=_value_] | a[href$=".pdf"] | 选择其 src 属性以 ".pdf" 结尾的所有 <a> 元素。 |
| [_attribute_*=_value_] | a[href*="w3schools"] | 选择其 href 属性值中包含 "abc" 子串的每个 <a> 元素。 |
| :active | a:active | 选择活动链接。 |
| ::after | p::after | 在每个 <p> 的内容之后插入内容。 |
| ::before | p::before | 在每个 <p> 的内容之前插入内容。 |
| :checked | input:checked | 选择每个被选中的 <input> 元素。 |
| :default | input:default | 选择默认的 <input> 元素。 |
| :disabled | input:disabled | 选择每个被禁用的 <input> 元素。 |
| :empty | p:empty | 选择没有子元素的每个 <p> 元素（包括文本节点）。 |
| :enabled | input:enabled | 选择每个启用的 <input> 元素。 |
| :first-child | p:first-child | 选择属于父元素的第一个子元素的每个 <p> 元素。 |
| ::first-letter | p::first-letter | 选择每个 <p> 元素的首字母。 |
| ::first-line | p::first-line | 选择每个 <p> 元素的首行。 |
| :first-of-type | p:first-of-type | 选择属于其父元素的首个 <p> 元素的每个 <p> 元素。 |
| :focus | input:focus | 选择获得焦点的 input 元素。 |
| :fullscreen | :fullscreen | 选择处于全屏模式的元素。 |
| :hover | a:hover | 选择鼠标指针位于其上的链接。 |
| :in-range | input:in-range | 选择其值在指定范围内的 input 元素。 |
| :indeterminate | input:indeterminate | 选择处于不确定状态的 input 元素。 |
| :invalid | input:invalid | 选择具有无效值的所有 input 元素。 |
| :lang(_language_) | p:lang(it) | 选择 lang 属性等于 "it"（意大利）的每个 <p> 元素。 |
| :last-child | p:last-child | 选择属于其父元素最后一个子元素每个 <p> 元素。 |
| :last-of-type | p:last-of-type | 选择属于其父元素的最后 <p> 元素的每个 <p> 元素。 |
| :link | a:link | 选择所有未访问过的链接。 |
| :not(_selector_) | :not(p) | 选择非 <p> 元素的每个元素。 |
| :nth-child(_n_) | p:nth-child(2) | 选择属于其父元素的第二个子元素的每个 <p> 元素。 |
| :nth-last-child(_n_) | p:nth-last-child(2) | 同上，从最后一个子元素开始计数。 |
| :nth-of-type(_n_) | p:nth-of-type(2) | 选择属于其父元素第二个 <p> 元素的每个 <p> 元素。 |
| :nth-last-of-type(_n_) | p:nth-last-of-type(2) | 同上，但是从最后一个子元素开始计数。 |
| :only-of-type | p:only-of-type | 选择属于其父元素唯一的 <p> 元素的每个 <p> 元素。 |
| :only-child | p:only-child | 选择属于其父元素的唯一子元素的每个 <p> 元素。 |
| :optional | input:optional | 选择不带 "required" 属性的 input 元素。 |
| :out-of-range | input:out-of-range | 选择值超出指定范围的 input 元素。 |
| ::placeholder | input::placeholder | 选择已规定 "placeholder" 属性的 input 元素。 |
| :read-only | input:read-only | 选择已规定 "readonly" 属性的 input 元素。 |
| :read-write | input:read-write | 选择未规定 "readonly" 属性的 input 元素。 |
| :required | input:required | 选择已规定 "required" 属性的 input 元素。 |
| :root | :root | 选择文档的根元素。 |
| ::selection | ::selection | 选择用户已选取的元素部分。 |
| :target | #news:target | 选择当前活动的 #news 元素。 |
| :valid | input:valid | 选择带有有效值的所有 input 元素。 |
| :visited | a:visited | 选择所有已访问的链接。 |


<br />
<br />style<br />
<br />颜色<br />background-color 背景色 <br />可以通过 #ff0000 二进制颜色 rgba()或者rgb()函数-rgba色彩 hsla()函数-hsla色彩  设置样式<br />
<br />**rgba(**_red,_** **_green_**, **_blue, alpha_**)  hsl(**_hue_**, **_saturation_**, **_lightness_**)**<br />_<br />_opacity设置透明度_<br />_<br />_设置背景图片_<br />background-image: url("图片路径")<br />
<br />设置重复规则<br />background-repeat: 

| repeat | 水平竖直都重复 |
| :--- | :--- |
| repeat-x | 仅x方向重复 |
| repeat-y | 仅y方向重复 |
| no-repeat | 不设置重复 |
| space | 尽量不发生裁剪的填充 |
| round | 无缝重复填充 |
| initial | 设置默认 |
| inherit | 规则继承自父元素 |


<br />
<br />background-attachment: scroll|fixed|local|initial|inherit; 背景附加
## Property Values
| Value | Description |
| :--- | :--- |
| scroll | 图片滚动(默认) |
| fixed | 图片固定 |
| local | 图片随元素滚动 |
| initial | 使用初始默认值 |
| inherit | 从父元素继承 |


<br />background-size: auto|_length_|cover|contain|initial|inherit;背景大小
## Property Values
| Value | Description |
| :--- | :--- |
| auto | 自动(默认) |
| _percentage_ | 通过百分比设置 |
| cover | 覆盖整个containter |
| contain | 使得整个图片可见 |
| initial | 字面 |
| inherit | 字面 |

border: _border-width_ _border-style_ _border-color_|initial|inherit;边界
## Property Values
| Value | Description |
| :--- | :--- |
| _border-width_ | Specifies the width of the border. Default value is "medium" |
| _border-style_ | Specifies the style of the border. Default value is "none" |
| _border-color_ | Specifies the color of the border. Default value is the color of the text |
| initial | Sets this property to its default value. [Read about _initial_](https://www.w3schools.com/cssref/css_initial.asp) |
| inherit | Inherits this property from its parent element. [Read about _inherit_](https://www.w3schools.com/cssref/css_inherit.asp) |

