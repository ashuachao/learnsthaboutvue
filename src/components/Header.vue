<template>
    <div class="adminheader">
      <div class="left">
        <h1 class="logo">货币基金</h1>
        <span class="slogan">后台管理系统</span>
        <div class="clear"></div>
      </div>
      <div class="right">
        <div class="userinfo">
          <!-- <img alt="aaa"> -->
          <span>welcome.管理员</span>
        </div>
        <div class="userinfotooltip">
          <div class="avatar">图片</div>
          <div class="userdata">
            <h4>laizhouwei611</h4>
            <ul>
              <li><a href="">编辑资料</a></li>
              <li><a href="">账号设置</a></li>
              <li><a href="">帮助</a></li>
              <li><a href="">退出</a></li>
            </ul>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {
  data () {
    return {
      // note: changing this line won't causes changes
      // with hot-reload because the reloaded component
      // preserves its current state and we are modifying
      // its initial state.
      msg: 'Hello World!'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.adminheader{
  background: #34445e;
  background: url("../assets/topheaderbg.png");
  border-bottom: 1px solid #303f59;
  padding: 8px 10px;
  position: relative;
}
.adminheader .left h1.logo{
  font-weight: normal;
  float: left;
  font-size: 30px;
  margin: 10px 0px;
}
.adminheader .left .slogan{
  color: #666;
  border-left: 1px solid #222;
  float: left;
  padding: 8px 10px;
  margin: 2px 10px;
}
.adminheader .left .clear{
  clear: both;
}
.adminheader .right{
  position: absolute;
  top: 10px;
  right: 10px;
}
.adminheader .right .userinfo{
  background: #32415a url(../assets/userinfoarrow.png) no-repeat right center;
  padding: 6px 18px 6px 6px;
  cursor: pointer;
}
.adminheader .right img{
  border: 1px solid #b9c1ce;
  vertical-align: middle;
}
.adminheader .right span{
  color: #ccc;
  display: inline-block;
  padding: 0 5px;
}
.adminheader .right .userinfotooltip{
  display: none;
  position: absolute;
  top: 48px;
  right: 0px;
  padding: 10px;
  min-width: 300px;
  border-radius: 2px;
  background: #fff;
  box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.2);
}
.adminheader .right .avatar{
  float: left;
}
.adminheader .right .userdata{
  margin-left: 105px;
}
.adminheader .right .userdata h4{
  font-size: 18px;
  color: #2d3c54;
  display: inline-block;
}
.adminheader .right .userdata ul{
  list-style: none;
  margin-top: 10px;
  padding: 0px;
  margin: 0px;
}
.adminheader .right .userdata ul li{
  display: block;
  margin-bottom: 1px;
}
.adminheader .right .userdata ul li a{
  display: block;
  padding: 5px;
  background: #f7f7f7;
  border-radius: 2px;
}
</style> 
