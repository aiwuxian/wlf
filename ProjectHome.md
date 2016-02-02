Wlf 是一款 windowless gui 框架，又名DirectUI框架。

WLF 旨在创建通用的Windows桌面DirectUI界面引擎，开发之初用于一款即时通讯系统，经过多年的开发已经非常成熟，现开源。
开源的目的是更好的推动此框架在3D方面的支持能力。
有兴趣者可以加入：
QQ群：125707498


> <h1>系统特性：</h1>
> <ul>
<blockquote><li><span>1.</span>支持XML配置资源，平台内的图片，字体等资源统一管理，方便调用。</li>
<li><span>2.</span>XML配置界面布局与自动排版，界面布局采用XML配置方式，也可以手动创建。在软件开发中经常遇到窗口拖动四个边后，窗口内容或空间需要在OnSize中手动布局控件的位置，所以才有了ResizableLib等专门用于布局的库，我们只需要手动配置一下即可，系统内的控件会自动布局，非常节省开发周期。</li>
<li><span>3.</span>高效图形渲染，传统的渲染方式不支持透明渲染，所以有时会采用Gdiplus等库，但是其所带来的效率低下我们深有体会，DirectUI渲染内部全部采用GDI渲染，极大地提高了速度。</li>
<li><span>4.</span>支持标准Win32控件，有时我们不得不在窗口中嵌套几个标准窗口控件，我们也支持标准窗口的布局与其他功能。</li>
<li><span>5.</span>支持ActiveX，DirectUI界面库支持Flash/IE等ActiveX控件。</li>
<li><span>6.</span>支持异形与透明窗口， 内部异形支持PNG与BMP异形。</li>
<li><span>7.</span>支持消息映射，我们采用开发中习惯的映射方式，有别于自创式映射方式。</li>
<li><span>8.</span>支持换肤与调色，支持软件换肤。</li>
<li><span>9.</span>全部Win32控件支持，丰富的办公及工业控件，包括比较复杂的树形等控件，及Outlook、Chart等控件。</li>
<li><span>10.</span>支持资源打包，DirectUI打包有别于其他的Zip等打包方式，我们采用自定义打包格式，提取方便，速度快。</li>
<li><span>11.</span>GIF库可单独支持。</li>
<li><span>12.</span>支持动画效果以及图片3D翻转、旋转、扭曲、透视投影等变换。</li>
</blockquote><blockquote></ul>