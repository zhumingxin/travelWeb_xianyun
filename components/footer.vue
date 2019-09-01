<template>
  <div class="container">
    <el-row type="flex" class="footer">
      <!-- <h1>这是底部组件</h1> -->
      <el-col class="travel_net">
        <h5>闲云旅游旅游网</h5>
        <ul>
          <li>上亿旅行者共同打造的"旅行神器"</li>
          <li>
            <span>60,000</span> 多个全球旅游目的地
          </li>
          <li>
            <span>600,000</span> 个细分目的地新玩法
          </li>
          <li>
            <span>760,000,000</span> 次攻略下载
          </li>
          <li>
            <span>38,000</span> 家旅游产品供应商
          </li>
        </ul>
      </el-col>

      <el-col class="about_us">
        <h5>关于我们</h5>
        <ul>
          <li>隐私政策 商标声明</li>
          <li>服务协议 游记协议</li>
          <li>商城平台服务协议</li>
          <li>网络信息侵权通知指引</li>
          <li>闲云旅游旅游网服务监督员</li>
          <li>网站地图加入闲云旅游</li>
        </ul>
      </el-col>

      <el-col class="service">
        <h5>旅行服务</h5>
        <ul>
          <li>旅游攻略 酒店预订</li>
          <li>旅游特价 国际租车</li>
          <li>旅游问答 旅游保险</li>
          <li>旅游指南 订火车票</li>
          <li>旅游资讯 APP下载</li>
        </ul>
      </el-col>

      <el-col class="qr_code">
        <img src="../assets/imgs/CODE.png" alt />
        <p>关注我们</p>
      </el-col>
    </el-row>
    <el-row class="footer_info">
      <p>京ICP备08001421号 京公网安备110108007702 Copyright © 2016-2019 博学谷 All Rights Reserved</p>
    </el-row>
  </div>
</template>

<script>
export default {};
</script>

<style lang="less" scoped>
.container {
  padding-top: 30px;
  margin-top: 250px;
  background-color: #333333;
  color: #cccccc;
  .footer {
    width: 1000px;
    margin: 0 auto;
    .travel_net {
      flex: 6;
      font-size: 12px;
    }
    .qr_code {
      flex: 6;
      text-align: center;
      font-size: 12px;
    }
    .about_us,
    .service {
      flex: 5;
    }
    li {
      font-size: 12px;
      line-height: 1.8;
      span {
        color: orange;
      }
    }
    h5 {
      font-weight: 400;
      font-size: 16px;
      margin-bottom: 10px;
    }
    .qr_code {
      img {
        width: 140px;
      }
    }
  }
  .footer_info {
    width: 1000px;
    margin: 0 auto;
    border-top: 1px solid #666666;
    margin-top: 20px;
    p {
      font-size: 12px;
      text-align: center;
      margin-top: 20px;
      padding: 50px 0;
    }
  }
}
</style>

