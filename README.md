# PersonalPage
个人网站：[个人3D立体时光相册](http://rmk.smilemurphy.club?_blank "个人3D立体时光相册")  

//js
var aTagArr = [].slice.apply(document.getElementsByTagName("a"));

aTagArr.forEach(function (e, i) {
  e.href.indexOf("_blank") > -1 ? e.target = "_blank" : null;
});

打开 index.html，即可看到我的个人主页，如下图所示：（这是我截取的图片，实际效果为动态图）

 ![image](https://github.com/TouchDreamRen/PersonalPage/raw/master/screenshots/screenshot.png)
