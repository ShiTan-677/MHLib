# MHLib
这是一个生成上海市闵行区图书馆预约凭证的网站。

## 目前已生成的预约凭证
#### **建议移动端使用微信打开以下网站**
- [2022/08/20](https://shitan-677.github.io/MHLib/220820.html "2022年8月20日的预约凭证")
- [2022/08/19](https://shitan-677.github.io/MHLib/220819.html "2022年8月19日的预约凭证")
- [2022/08/18](https://shitan-677.github.io/MHLib/220818.html "2022年8月18日的预约凭证")
- [2022/08/17](https://shitan-677.github.io/MHLib/220817.html "2022年8月17日的预约凭证")
- [2022/08/16](https://shitan-677.github.io/MHLib/220816.html "2022年8月16日的预约凭证")
- [2022/08/14](https://shitan-677.github.io/MHLib/220814.html "2022年8月14日的预约凭证")
- [2022/08/13](https://shitan-677.github.io/MHLib/220813.html "2022年8月13日的伪造预约凭证")
- [2022/08/12](https://shitan-677.github.io/MHLib/220812.html "2022年8月12日的伪造预约凭证")
- [2022/08/11](https://shitan-677.github.io/MHLib/%E9%97%B5%E8%A1%8C%E5%8C%BA%E5%9B%BE%E4%B9%A6%E9%A6%860811.html "2022年8月11日的伪造预约凭证")

## 项目更新与预约
受技术力限制，本项目无法批量生成凭证，所有凭证均为项目所有者手动更新。因此当所有者不打算前往图书馆时，本项目不会主动生成凭证。**如果您有使用生成凭证的需求，请提前在[`issue`](https://github.com/ShiTan-677/MHLib/issues "问题")中预约。但是请注意，项目所有者可以选择不提供生成凭证。**

## 项目实现原理
本项目通过复刻预约网页源代码，复刻预约页面。但是由于项目所有者没有能力在普通浏览器导入微信的登录信息，且没有能力使用微信浏览器复刻网页，因此选择通过修改图片的方式生成凭证。此后将生成凭证上传至~~[图床](https://imgloc.com/ "某免费图片外链网站")~~库，并将预约页面部分图片、图标超链接至生成凭证以实现项目预期效果。

## 项目灵感来源
上海市闵行区图书馆于2022年8月9日重新开馆。但预约人数限制在100人，预约难度极大。由于项目所有者有和同伴前往图书馆的意愿，所以也曾使用过共享截图、修改图片、带同行人员混入等方式。但是由于2022年8月11日~~起~~（疑似只有当天）安保人员检查预约凭证的手段升级，由仅目视检查日期升级到手动检查确认页面非截图可滑动，并配上广播「请提供实时预约凭证，截图无效」。因此「魔高一尺，道高一丈」，项目所有者决定开发本项目，生成更真实的预约凭证页面。
