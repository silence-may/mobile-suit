# 移动端适配
### media query 移动端尺寸参考
> @media screen and ( min-width: 212px){/*213px显示屏样式 LG Optimus One*/}<br/>
@media screen and ( min-width: 319px){/*320px显示屏样式 苹果4/4S/5C/5S黑莓Z30 */}<br/>
@media screen and ( min-width: 359px){/*360px显示屏样式 索尼Z1*/}<br/>
@media screen and ( min-width: 383px){/*384px显示屏样式 黑莓Z10 谷歌 Nexus 6 LG Optimus G*/}<br/>
@media screen and ( min-width: 399px){/*399px显示屏样式 三星galaxyNote*/}<br/>
@media screen and ( min-width: 414px){/*414px显示屏样式 苹果6plus*/}<br/>
@media screen and ( min-width: 423px){/*424px显示屏样式 LG 4X */}<br/>
@media screen and ( min-width: 479px){/*480px显示屏样式 索尼MT27i Xperia sola*/}<br/>
@media screen and ( min-width: 539px){/*640px显示屏样式 摩托罗拉Droid3/4/Razr Atrix 4g*/}<br/>
@media screen and ( min-width: 639px){/*640px显示屏样式*/}<br/>
@media screen and ( min-width: 640px){/*640px以上显示屏样式*/}<br/>

### 可用媒体查询尺寸参考
> @charset "utf-8";<br/>
html {font-size:43px;}<br/>
@media screen and (min-width: 360px){
    html{font-size:48px;}
}<br/>
//iPhone6s尺寸,375,1rem=50px,设计稿为750,1rem=100px<br/>
@media screen and (min-width:375px) {   
    html {font-size: 50px;}
}<br/>
@media screen and (min-width:414px) {
    html {font-size: 55px; }
}<br/>
@media screen and (min-width:480px) {
    html {font-size: 64px;}
}<br/>
@media screen and (min-width:640px){
    html {font-size: 85px;}
}<br/>
@media screen and (min-width:750px){
    html {font-size: 100px;}
}
