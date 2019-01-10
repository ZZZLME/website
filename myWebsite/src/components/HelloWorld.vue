/*
 * @Author: zzz 
 * @Date: 2019-01-08 18:17:48 
 * @Last Modified by:   zzz 
 * @Last Modified time: 2019-01-08 18:17:48 
 */
<template>
  <!-- <div> -->
  <div class="background_color">
    <div class="m_head">
      <div class="head_left">
        <Menu mode="horizontal" theme="dark" active-name="1">
          <MenuItem name="1">
            <Icon type="ios-paper"/>首页
          </MenuItem>
          <MenuItem name="2">
            <Icon type="ios-people"/>个人博客
          </MenuItem>
          <MenuItem name="3">
            <Icon type="ios-construct"/>打赏
          </MenuItem>
        </Menu>
      </div>
      <div class="head_right">
        <ul>
          <li>登录/注册</li>
          <li style="padding: 0px 20px;">
            <svg class="icon myIconStyle" aria-hidden="true">
              <use xlink:href="#icon-github"></use>
            </svg>
          </li>
          <li style="padding: 0px 10px 0px 0px;">
            <svg class="icon myIconStyle" aria-hidden="true">
              <use xlink:href="#icon-shezhi1"></use>
            </svg>
          </li>
        </ul>
      </div>
    </div>
    <div class="m_body">
      <p style="padding: 100px 200px 20px 200px;font-size: 16px;text-indent:2em">
        本网站所有的素材和源码都是由本人提供，目的不仅是为了给自己一个学习锻炼的实践方式，也是互相学习交流的桥梁。网站开发的所有费用都是由本人
        承担 (域名，服务器，cdn存储) ，如果您觉得这个网站能够给到您帮助和服务，您可以扫描下面任意二维码，设置任意金额来支持我继续把它做下去。
      </p>
      <p style="padding: 10px 200px 20px 200px;font-size: 16px;text-indent:2em">
        希望未来能提供更多更好的免费服务和分享给大家。我也会将支持
        我的人给记录下来，您也是这个网站贡献者的一部分，谢谢您的支持和鼓励。
      </p>
      <div>
        <ul style="display: flex;justify-content: center;">
          <li style="width: 300px;height: 300px;margin:30px 100px">
            <img src="../assets/bg1.jpg" width="300px" height="300px" alt>
          </li>
          <li style="width: 300px;height: 300px;margin:30px 100px">
            <img src="../assets/bg1.jpg" width="300px" height="300px" alt>
          </li>
        </ul>
      </div>
    </div>
    <div style="background-color: #2a323b94;">
      <div class="m_foot">
        <ul>
          <li style="padding: 0px 0px 0px 20px;">qq邮箱:1262495218@qq.com</li>
          <li>
            <span>GitHub</span>
            <span style="padding: 0px 20px;">友情链接</span>
          </li>
        </ul>
      </div>
    </div>
  </div>
  <!-- </div> -->
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
body {
  margin: 0;
  padding: 0;
}
ul {
  list-style: none;
}
.background_color {
  /* background-color: #2a323b94; */
  background: url("../assets/bg.jpg") no-repeat;
  /* background: url("../assets/bg.jpg") no-repeat 4px 5px;
  height: 100%;
  width: 100%; */
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  min-width: 1000px;
  z-index: -10;
  zoom: 1;
  background-color: #fff;
  background-repeat: no-repeat;
  background-size: cover;
  -webkit-background-size: cover;
  -o-background-size: cover;
  background-position: center 0;
}
.m_head {
  filter: alpha(Opacity=60);
  -moz-opacity: 0.6;
  opacity: 0.6;
  background-color: #2a323b94;
  /* height: 100px; */
  width: 100%;
  display: flex;
  justify-content: space-between;
}
.head_left {
  /* background-color: #888; */
  height: 50px;
  width: 50%;
}
.head_right {
  /* background-color: #666; */
  /* height: 50px; */
  filter: alpha(Opacity=60);
  -moz-opacity: 0.6;
  opacity: 0.6;
  background-color: #2a323b94;
  width: 50%;
}
.head_right ul {
  display: flex;
  list-style: none;
  color: #fff;
  justify-content: flex-end;
  line-height: 50px;
}
.m_body {
  background-color: #2a323b94;
  height: 848px;
  width: 100%;
  color: #fff;
}
.m_foot {
  filter: alpha(Opacity=60);
  -moz-opacity: 0.6;
  opacity: 0.6;
  background-color: #2a323b94;
  height: 40px;
  width: 100%;
  color: #fff;
}
.m_foot ul {
  display: flex;
  justify-content: space-between;
  line-height: 40px;
}
/* 自定义图标样式 */
.myIconStyle {
  width: 20px;
  height: 20px;
}
/* 框架自定义样式 */
.ivu-menu-dark {
  filter: alpha(Opacity=60);
  -moz-opacity: 0.6;
  opacity: 0.6;
  background: #2a323b94;
}
.ivu-menu-horizontal {
  height: 50px;
  line-height: 50px;
}
</style>
