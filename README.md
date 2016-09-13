# practice
<p style="text-indent:2em;">自己太菜了练练手吧！</p>
<p style="text-indent:2em;">感觉所有人都瞧不起我的的兴趣啊！坚持吧，谁让前端这么有意思，当然我很菜，但我有梦想啊！我的梦想是成为全栈工程师，我不是很喜欢我现在的专业，感觉我将来会是一种一眼望穿生死的状态。人活着不能那么没志气，谢谢大家！<br/>
<h3>《希望我的热情和潜力能让你多看我一眼！！！》</h3><br/>
<h3>我的邮箱是：sevenlondon@yeah.net</h3> <br/>
<h3>我的微博是：@让我冷静一个月。</h3>
</p>
<p style="text-indent:2em;">实践是检验真理的唯一标准。所以就练一练，反正大家都看不到，生命在于折腾。学前端的好处可能就是顺带把英语也好好学了学！</p>
<h1 style="text-indent:2em;">那么现在就开始吧！</h1>
<h3 style="text-indent:2em;">如果我将来去应聘前端，我的Github可能就是我所有的项目。是这个平台见证我一步步的成长。</h3>
<h2>一、一个静态的登录界面。</h2>
<p style="text-indent:2em;">哦~我就是爱熬夜，别叫我停下来。这个登录界面主要是定位，定位，圆角矩形，外边距，表单的练习。CSS3确实比CSS2要牛逼很多，这个是肯定的。一直有一个疑问就是margin:auto到底是怎么用的，我回头再好好研究一下吧。看图吧，简直就一个东施（我的），一个西施（设计图的），不忍直视了我！</p><hr/>
<p>这是我的</p>
<img style="width:400px; height:225px;float:left;" src="https://raw.githubusercontent.com/seven810436/practice/master/sign-in-page/%E6%90%9C%E7%8B%97%E6%88%AA%E5%9B%BE20160821004205.png"><br/><hr/>
<p>这是别人的</p>
<img style="width:400px; height:225px;float:left;" src="https://raw.githubusercontent.com/seven810436/practice/master/sign-in-page/16sucai_201606181008.jpg"><hr/>
<p>对登录界面进行了完善，加入了自动获得焦点和表单提示信息。</p>
<h2>二、一个半静态百度首页。</h2>
<p>这个做的还是很粗鄙的，学艺不精，我会继续努力争取做出一个一模一样的网页。下一个目标是模仿战网做一个静态网页。</p>
<p>这是我的</p>
<img style="width:400px; height:225px;float:left;" src="https://raw.githubusercontent.com/seven810436/practice/master/baidu-first-page/%E6%90%9C%E7%8B%97%E6%88%AA%E5%9B%BE20160821000450%E4%BB%BF.png"><br/><hr/>
<p>这是百度的</p>
<img style="width:400px; height:225px;float:left;" src="https://raw.githubusercontent.com/seven810436/practice/master/baidu-first-page/%E6%90%9C%E7%8B%97%E6%88%AA%E5%9B%BE20160820194347.png"><hr/>
<h2>三、战网首页。</h2>
<p>模仿的这个战网首页基本把所有的链接效果做出来了，里面运用最多的是图片拼合，还有对布局是一个很重要的练习。</p>
<p>这是我的</p>
<img style="width:400px; height:225px;float:left;" src="https://raw.githubusercontent.com/seven810436/practice/master/battlenet-first-page/battlenet1.jpg"><br/><hr>
<p>这是战网的</p>
<img style="width:400px; height:225px;float:left;" src="https://raw.githubusercontent.com/seven810436/practice/master/battlenet-first-page/battlenet.jpg"><hr>
<h2>四、渐变练习</h2>
<p>渐变来说应该是现阶段CSS3里兼容性最差的了。</p>
<img style="width:400px; height:225px;float:left;" src="https://raw.githubusercontent.com/seven810436/practice/master/gradient/new_file.html.png"><hr>
<h2>五、过渡和简单动画</h2>
<p>过渡和动画相对来说比较简单，但是需要完全掌握是比较麻烦的，属性比较多，像我这种菜鸟往往难以驾驭，需要注意的是：
       <pre>1、transition有四个属性值，分别是：
			 transition-property（要过渡的属性名称）；
			 transition-duration（要过渡的时间）;
			 transition-timing-function（过渡时间曲线）；
			 transition-delay（规定过渡何时开始）；</pre>
			 <pre>2、nimation常用的六个值：
			 animation-name；（动画名称）
			 animation-duration；（动画需要多长时间完成）
			 animation-timing-function；（动画的时间曲线）
			 animation-delay；（规定动画何时开始）
			 animation-iteration-count；（规定动画循环次数，默认值：1，其他有n或者infinite）
			 animation-direction；（规定是否下一周期逆向播放，默认值为normal，reverse：反向播放，alternate：奇正偶反，alternate-reverse：偶正奇反）；
			 在@keyframes中创建动画，在绑定的选择器中至少需要两个属性：名称和时长。</pre>
			 </p>
<img src="https://raw.githubusercontent.com/seven810436/practice/master/transition-and-animation/GIF3.gif"><hr>
<h2>六、稍复杂的动画</h2>
<p>这个是animation的高级运用，其中在@keyframes中用到了以百分数代替from和to，为了得到良好的兼容性往往以0%开始，以100%结束，还可以设置其位置，这样可以更好的控制动画的运行。如<pre>@keyframes myfirst{
				0% {
					background: crimson;
					left: 0px;
					top: 0px;
				}
				25% {
					background: yellow;
					left: 250px;
					top: 0px;
				}
				50% {
					background: aqua;
					left: 250px;
					top: 250px;
				}
				75% {
					background: burlywood;
					left: 0px;
					top: 250px;
				}
				100% {
					background: azure;
					left: 0px;
					top: 0px;
				}
			}</pre>在给div设置样式时需要注意position属性，如果不设置会造成动画位置不变。在animation和keyframes前加上-mos-、-ms-、-weblit-是代码具有良好的兼容性。</p>
<img src="https://raw.githubusercontent.com/seven810436/practice/master/animation/GIF4.gif"><hr>
<h2>七、多列</h2>
<p>哦~我的天哪！这多列兼容也是相当感人。</p>
<img src="https://raw.githubusercontent.com/seven810436/practice/master/column/%E6%90%9C%E7%8B%97%E6%88%AA%E5%9B%BE20160911173845.png"><hr>
<h2>八、CSS3图片样式运用——简直awesome</h2>
<p>CSS3图片样式简直帅，没得说。一定要掌握的。</p>
<img src="https://github.com/seven810436/practice/blob/master/CSS3-IMG/GIF5.gif"><br><img src="https://github.com/seven810436/practice/blob/master/CSS3-IMG/%E5%9B%BE%E7%89%87.jpg"><hr>
