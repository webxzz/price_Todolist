<template>
  <div class="wrap">
    <header class="header">
      <div class="header_top">
        <div class="logo">
          <!-- 淘宝logo -->
        </div>
        <div class="sousuo" @click="search">
          <p>
            <span>
              <svg class="icon" aria-hidden="true">
                <use xlink:href="#icon-sousuo"></use>
              </svg>
            </span>
            <span>寻找宝贝店铺</span>
          </p>
        </div>
      </div>
    </header>
    <!-- 主体 -->
    <main class="main">
      <div class="rotation">
        <img
          src="//img.alicdn.com/imgextra/i1/6000000007810/O1CN01PrcDPW27Z1zDSPebH_!!6000000007810-0-lubanimage.jpg"
          alt=""
        />
      </div>
      <div class="banyuan">
        <!-- 轮播半圆边 -->
      </div>
      <div class="signbar">
        <div class="signbar_nav">
          <p>
            <img
              src="https://gw.alicdn.com/tfs/TB1OIxTcLc3T1VjSZLeXXbZsVXa-183-144.png?getAvatar=1"
              alt=""
            />
          </p>
          <p>天猫新品</p>
        </div>
        <div class="signbar_nav">
          <p>
            <img
              src="https://gw.alicdn.com/tfs/TB1LvIxVAvoK1RjSZFDXXXY3pXa-183-144.png?getAvatar=1"
              alt=""
            />
          </p>
          <p>今日爆款</p>
        </div>
        <div class="signbar_nav">
          <p>
            <img
              src="https://gw.alicdn.com/tfs/TB19uWKXkCy2eVjSZPfXXbdgpXa-183-144.png?getAvatar=1"
              alt=""
            />
          </p>
          <p>天猫国际</p>
        </div>
        <div class="signbar_nav">
          <p>
            <img
              src="https://gw.alicdn.com/tfs/TB1DaMyVpzqK1RjSZFoXXbfcXXa-185-144.png?getAvatar=1"
              alt=""
            />
          </p>
          <p>饿了么</p>
        </div>

        <div class="signbar_nav">
          <p>
            <img
              src="https://gw.alicdn.com/tfs/TB1FucwVwHqK1RjSZFgXXa7JXXa-183-144.png?getAvatar=1"
              alt=""
            />
          </p>
          <p>天猫超市</p>
        </div>
        <div class="signbar_nav">
          <p>
            <img
              src="https://gw.alicdn.com/tfs/TB1llI3f4n1gK0jSZKPXXXvUXXa-183-144.png?getAvatar=1"
              alt=""
            />
          </p>
          <p>充值中心</p>
        </div>
        <div class="signbar_nav">
          <p>
            <img
              src="https://gw.alicdn.com/tfs/TB1O_AyVwHqK1RjSZFPXXcwapXa-183-144.png?getAvatar=1"
              alt=""
            />
          </p>
          <p>机票酒店</p>
        </div>
        <div class="signbar_nav">
          <p>
            <img
              src="https://gw.alicdn.com/tfs/TB19yZJVBLoK1RjSZFuXXXn0XXa-183-144.png?getAvatar=1"
              alt=""
            />
          </p>
          <p>金币庄园</p>
        </div>
        <div class="signbar_nav" @click="alipaimai">
          <p>
            <img
              src="https://gw.alicdn.com/tfs/TB16ZYDk4n1gK0jSZKPXXXvUXXa-183-144.png?getAvatar=1"
              alt=""
            />
          </p>
          <p>阿里拍卖</p>
          
        </div>
        <div class="signbar_nav">
          <p>
            <img
              src="https://gw.alicdn.com/tfs/TB19dcwVyrpK1RjSZFhXXXSdXXa-183-144.png?getAvatar=1"
              alt=""
            />
          </p>
          <p>淘宝吃货</p>
        </div>
      </div>
      <!-- 聚划算 -->
      <div class="commodity">
        <div class="commodity_nav">
          <p>聚划算</p>
          <p>品牌折扣</p>
          <p>
            <img
              src="https://gw.alicdn.com/tfs/TB1CmfrECzqK1RjSZFjXXblCFXa-200-200.jpg_125x125q90_.webp"
              alt=""
            />
          </p>
        </div>
        <div class="commodity_nav">
          <p></p>
          <p>划算好货</p>
          <p>
            <img
              src="https://gw.alicdn.com/tfs/TB1q0TGExjaK1RjSZFAXXbdLFXa-200-200.jpg_125x125q90_.webp"
              alt=""
            />
          </p>
        </div>
        <div class="commodity_nav">
          <p>聚划算</p>
          <p>品牌折扣</p>
          <p>
            <img
              src="https://gw.alicdn.com/tfs/TB1CmfrECzqK1RjSZFjXXblCFXa-200-200.jpg_125x125q90_.webp"
              alt=""
            />
          </p>
        </div>
        <div class="commodity_nav">
          <p>聚划算</p>
          <p>品牌折扣</p>
          <p>
            <img
              src="https://gw.alicdn.com/tfs/TB1CmfrECzqK1RjSZFjXXblCFXa-200-200.jpg_125x125q90_.webp"
              alt=""
            />
          </p>
        </div>
        <div class="commodity_nav">
          <p>聚划算</p>
          <p>品牌折扣</p>
          <p>
            <img
              src="https://gw.alicdn.com/tfs/TB1CmfrECzqK1RjSZFjXXblCFXa-200-200.jpg_125x125q90_.webp"
              alt=""
            />
          </p>
        </div>
        <div class="commodity_nav">
          <p>聚划算</p>
          <p>品牌折扣</p>
          <p>
            <img
              src="https://gw.alicdn.com/tfs/TB1CmfrECzqK1RjSZFjXXblCFXa-200-200.jpg_125x125q90_.webp"
              alt=""
            />
          </p>
        </div>
        <div class="commodity_nav">
          <p>聚划算</p>
          <p>品牌折扣</p>
          <p>
            <img
              src="https://gw.alicdn.com/tfs/TB1CmfrECzqK1RjSZFjXXblCFXa-200-200.jpg_125x125q90_.webp"
              alt=""
            />
          </p>
        </div>
        <div class="commodity_nav">
          <p>聚划算</p>
          <p>品牌折扣</p>
          <p>
            <img
              src="https://gw.alicdn.com/tfs/TB1CmfrECzqK1RjSZFjXXblCFXa-200-200.jpg_125x125q90_.webp"
              alt=""
            />
          </p>
        </div>
        <div class="commodity_nav">
          <p>聚划算</p>
          <p>品牌折扣</p>
          <p>
            <img
              src="https://gw.alicdn.com/tfs/TB1CmfrECzqK1RjSZFjXXblCFXa-200-200.jpg_125x125q90_.webp"
              alt=""
            />
          </p>
        </div>
        <div class="commodity_nav">
          <p>聚划算</p>
          <p>品牌折扣</p>
          <p>
            <img
              src="https://gw.alicdn.com/tfs/TB1CmfrECzqK1RjSZFjXXblCFXa-200-200.jpg_125x125q90_.webp"
              alt=""
            />
          </p>
        </div>
        <div class="commodity_nav">
          <p>聚划算</p>
          <p>品牌折扣</p>
          <p>
            <img
              src="https://gw.alicdn.com/tfs/TB1CmfrECzqK1RjSZFjXXblCFXa-200-200.jpg_125x125q90_.webp"
              alt=""
            />
          </p>
        </div>
        <div class="commodity_nav">
          <p>聚划算</p>
          <p>品牌折扣</p>
          <p>
            <img
              src="https://gw.alicdn.com/tfs/TB1CmfrECzqK1RjSZFjXXblCFXa-200-200.jpg_125x125q90_.webp"
              alt=""
            />
          </p>
        </div>
      </div>
      <!-- 猜你喜欢 -->
      <div class="like">
        <img
          src="https://img.alicdn.com/tfs/TB1V2eQrKSSBuNjy0FlXXbBpVXa-966-114.png"
          alt=""
        />
      </div>
      <div class="like_sp">
        <div class="sp_max">
          <div class="sp_a">
            <div class="sp_img">
              <img
                src="//gw.alicdn.com/bao/uploaded/i3/66219476/O1CN01Z5valg2Js3mK9AFEb_!!66219476.jpg_320x320q90.jpg_.webp"
                alt=""
              />
            </div>
            <div class="sp_xx">芭婷护创软膏凝胶官方正品官网修护创软膏复膏</div>
            <div class="sp_jg">
              <span>￥299</span>
              <span>520人已购买</span>
            </div>
          </div>
          <div class="sp_a">
            <div class="sp_img">
              <img
                src="//gw.alicdn.com/bao/uploaded/i3/66219476/O1CN01Z5valg2Js3mK9AFEb_!!66219476.jpg_320x320q90.jpg_.webp"
                alt=""
              />
            </div>
            <div class="sp_xx">芭婷护创软膏凝胶官方正品官网修护创软膏复膏</div>
            <div class="sp_jg">
              <span>￥299</span>
              <span>520人已购买</span>
            </div>
          </div>
          <div class="sp_a">
            <div class="sp_img">
              <img
                src="//gw.alicdn.com/bao/uploaded/i3/66219476/O1CN01Z5valg2Js3mK9AFEb_!!66219476.jpg_320x320q90.jpg_.webp"
                alt=""
              />
            </div>
            <div class="sp_xx">芭婷护创软膏凝胶官方正品官网修护创软膏复膏</div>
            <div class="sp_jg">
              <span>￥299</span>
              <span>520人已购买</span>
            </div>
          </div>
          <div class="sp_a">
            <div class="sp_img">
              <img
                src="//gw.alicdn.com/bao/uploaded/i3/66219476/O1CN01Z5valg2Js3mK9AFEb_!!66219476.jpg_320x320q90.jpg_.webp"
                alt=""
              />
            </div>
            <div class="sp_xx">芭婷护创软膏凝胶官方正品官网修护创软膏复膏</div>
            <div class="sp_jg">
              <span>￥299</span>
              <span>520人已购买</span>
            </div>
          </div>
          <div class="sp_a">
            <div class="sp_img">
              <img
                src="//gw.alicdn.com/bao/uploaded/i3/66219476/O1CN01Z5valg2Js3mK9AFEb_!!66219476.jpg_320x320q90.jpg_.webp"
                alt=""
              />
            </div>
            <div class="sp_xx">芭婷护创软膏凝胶官方正品官网修护创软膏复膏</div>
            <div class="sp_jg">
              <span>￥299</span>
              <span>520人已购买</span>
            </div>
          </div>
          <div class="sp_a">
            <div class="sp_img">
              <img
                src="//gw.alicdn.com/bao/uploaded/i3/66219476/O1CN01Z5valg2Js3mK9AFEb_!!66219476.jpg_320x320q90.jpg_.webp"
                alt=""
              />
            </div>
            <div class="sp_xx">芭婷护创软膏凝胶官方正品官网修护创软膏复膏</div>
            <div class="sp_jg">
              <span>￥299</span>
              <span>520人已购买</span>
            </div>
          </div>
        </div>
      </div>
    </main>
    <!-- 底部 -->
    <footer class="footer">
      <div class="footer_sy">
        <p id="ss">
          <svg class="icon" aria-hidden="true">
            <use xlink:href="#icon-shouye"></use>
          </svg>
        </p>
        <p>首页</p>
      </div>
      <div class="footer_sy">
        <p>
          <svg class="icon" aria-hidden="true">
            <use xlink:href="#icon-gouwuche"></use>
          </svg>
        </p>
        <p>购物车</p>
      </div>
      <div class="footer_sy">
        <p>
          <svg class="icon" aria-hidden="true">
            <use xlink:href="#icon-dingdanliebiao"></use>
          </svg>
        </p>
        <p>订单列表</p>
      </div>
      <div class="footer_sy">
        <p>
          <svg class="icon" aria-hidden="true">
            <use xlink:href="#icon-wode"></use>
          </svg>
        </p>
        <p>我的淘宝</p>
      </div>
      <div class="footer_sy">
        <p>
          <svg class="icon" aria-hidden="true">
            <use xlink:href="#icon-gengduo"></use>
          </svg>
        </p>
        <p>更多</p>
      </div>
      <div id="hu">
        <a href="../html/taobao.html">
          <!-- <img src="../img/02.png" alt=""> -->
        </a>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: "Home",
  methods: {
    search() {
      this.$router.push({ name: "search" });
    },
    alipaimai(){
        this.$router.push({
            name:'alipaimai'
        })
    },
  }
};
</script>

<style  scoped>
.icon {
  width: 0.16rem;
  height: 0.16rem;
  vertical-align: -0.15em;
  fill: currentColor;
  overflow: hidden;
}
.wrap {
  width: 1000px;
  height: 100%;
  display: flex;
  flex-direction: column;
}
.header {
  width: 100%;
  height: 0.37rem;
  /* background-color: #ccc; */
  background-color: rgb(255, 133, 42);
}
.header_top {
  width: 3.75rem;
  height: 0.37rem;
  background-color: rgb(255, 133, 42);
  margin: 0 auto;
  display: flex;
  flex-wrap: wrap;
  align-content: space-between;
  align-items: center;
  justify-content: space-around;
}
.logo {
  width: 0.35rem;
  height: 0.37rem;
  /* background: red; */
  background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAD8AAAAwCAMAAACR11I4AAAABGdBTUEAALGPC/xhBQAAAAFzUkdCAK7OHOkAAADwUExURUdwTP//////////////////////////7v//7f//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////AP//AP//////////////////////////////AP//AP//AP//AP//AP//AP//////AP//AP//AP//AP//AP//AP//////AIlGdUwAAABOdFJOUwD8w3w45vkBBPYt3gqWYYieMGvry+/jvyZmPNAYBx6jbylXNBvaTUjUFA+vsw1Ad4PXUyMSqY3zSw/HEFxDkXO6oepxVMf7pqvePzXRHLxDEf8AAAORSURBVEjHnVZpY6IwEOVSQUABFbxARWu13lq1W2vt9twT//+/WXJBiOjudr6QYx6ZvHmZhOPSTHy09r0c91nLlYLQto317j9AX+SomQ+QDeJZd+h1qrvzIb18P76//cSdNsbXYDBSTRcqaIDPCBvfS4F/PQJ7v0M9AXmrLnfjt0oBa85SZvZ7d0T2/AV0q9hvmTeyQarZ12nLhwYDKOLln4LzVkyE8EbwL2FHzpy6V9TFYGDT0TjuufVrCWTDaO9XxHf1MObJxJrCv1L7d+14VcMfskx7YzL7QI1+Q/hXKnn8aOmmppo4lCbxmPzyfDz++hG2hihfil49Kz4R/0CkU8j9hrnj1nBtfRhmIePo7V4KXr5H+EyKHC0w8dThuDokapC6hWscwP50SioFlUL47cEkZqWbYdNbdUxpet33C9ZBLBZBsCrC63T82KotoO9J+ZxwGsDJYM+X29jcUlFowlnhwTWJRCJMKNmKFUlSc87C7R5NQJ3sGpJVNlk4n1VQQ3HG65a+EX0NenToAx5Gv0DdbBt2u+Hf+M1Qk0NSTDRzlWR5Qk4R6tajE6NDHmeBkE+WIgbPbdGwQeirqTQ9uX6Ou4zHRWUca6qGYygkHRl8Tht6QNf4jAl0zubweKth89Z/KNQs6zATRR05boXyQM1UsoS0KzRcTqxl2jinUnDJpqHrgBJTbD4Ya/4FPwDcqKl4IIusfAHPbxdGk+JPSOJ1vKWVoT9uinNxdmjPcS01q15zEtdMheUfHp1sLAmGfybQXEoN5HJQtlLS00wjmmsGSf3EpcMG7JhTTz6Dn0DJ15P6RdEr0UhYYnlb8OFZSBA1EStb8C0EJ2JzUcWAukdShHiJwu9EcI2CijZnzm9oj3GceHd5Cu9wuWkLkQ7yN8L4ZgTvowGLOt0etdOySA5Y0InTv43gK3TBKztqz33Qnp5oSIrLR5R+rYEGWhyFzyy9Xn5GIUsC3pYVUNEC+4j/Df7Gp2m3NNMA7aWwgpHivMLwGfPeSbn4GwUXkpRdxs+jBeGOZ+IxlSRYMeroJbQwqhT7OPvmlrhFN2bdpsCjwiQhXpyqQEUabUa+lJrdwsciU1GFVruuMaVvv00uL90TvPkPr8ThnDxiWtHYFPF1fwknNNZhQXh0ImYc+gHVHTHvkZMrn2E0GDGvi3wr417AV5lbsH/qol0K360fRoRnVe9rn3qWu6tut9O7SYz9AWZChIYAa6nHAAAAAElFTkSuQmCC)
    50% no-repeat;
  background-size: 0.27rem 0.2rem;
}
.logo > img {
  width: 0.27rem;
  height: 0.2rem;
}
.sousuo {
  width: 3.24rem;
  height: 0.25rem;
  display: block;
  font-size: 0;
  background-color: rgb(255, 78, 34);
  border-radius: 5px;
  display: flex;
  justify-content: space-around;
}
.sousuo > p {
  width: 0.98rem;
  height: 0.25rem;
  /* background: red; */
  color: rgb(240, 224, 220);
  font-size: 13px;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  align-content: space-around;
}
.main {
  width: 1000px;
  background: #f2f2f2;
  flex: 1;
  overflow-y: scroll;
}
.banyuan {
  width: 3.75rem;
  height: 0.1rem;
  /* background: red; */
  background: url("https://gw.alicdn.com/tfs/TB1vMMwChTpK1RjSZFMXXbG_VXa-1125-30.png")
    no-repeat;
  background-size: 3.75rem 0.1rem;
  margin: 0 auto;
  z-index: 99;
  position: relative;
  top: -0.09rem;
}
.rotation {
  width: 3.75rem;
  height: 1.2rem;
  background: red;
  margin: 0 auto;
}
.rotation > img {
  width: 3.75rem;
  height: 1.2rem;
}
.signbar {
  width: 3.6rem;
  height: 1.56rem;
  /* background: palegreen; */
  margin: 0 auto;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  align-content: space-around;
}
.signbar_nav {
  width: 0.61rem;
  height: 0.67rem;
  /* background: red; */
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
}
.signbar_nav > p:nth-child(1) > img {
  width: 0.61rem;
  height: 0.48rem;
}
.signbar_nav > p:nth-child(2) {
  font-size: 0.1rem;
  color: rgb(102, 102, 102);
}
.commodity {
  width: 3.6rem;
  height: 3.63rem;
  background: #fff;
  border-radius: 0.1rem;
  margin: 0 auto;
  margin-top: 0.1rem;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}
.commodity_nav {
  width: 0.9rem;
  height: 1.21rem;
  background: #fff;
  border-radius: 0.1rem;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  align-content: space-around;
  flex-direction: column;
}
.commodity_nav > p:nth-child(1) {
  font-size: 0.18rem;
  font-weight: 800;
}

.commodity_nav > p:nth-child(3) > img {
  width: 0.6rem;
  height: 0.6rem;
  /* background: rgb(238, 197, 197); */
}
.like {
  width: 3.6rem;
  height: 0.47rem;
  margin: 0 auto;
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
  align-content: space-around;
}
.like > img {
  width: 1.61rem;
  height: 0.19rem;
}
.like_sp {
  width: 100%;
  display: flex;
}
.sp_max {
  width: 3.6rem;
  /* height: 2.60rem; */
  /* background: red; */
  margin: 0 auto;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
}
.sp_a {
  width: 1.71rem;
  height: 2.6rem;
  margin: 0.05rem 0;
  background: #fff;
  border-radius: 0.1rem;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  align-content: space-around;
}
.sp_img {
  width: 1.71rem;
  height: 1.71rem;
  /* background:peru; */
}
.sp_img > img {
  width: 1.71rem;
  height: 1.71rem;
  margin: 0.08rem 0 0 0;
}
.sp_xx {
  width: 1.43rem;
  height: 0.3725rem;
  /* background: palegreen; */
  margin-top: 0.1rem;
  font-size: 0.11rem;
}
.sp_jg {
  width: 1.25rem;
  height: 0.2rem;
  /* background: papayawhip; */
}
.sp_jg > span:nth-child(1) {
  color: #ff5500;
  font-size: 0.14rem;
  margin: 0 0.05rem;
}
.sp_jg > span:nth-child(2) {
  font-size: 0.11rem;
  color: #999999;
  margin-top: 0.02000000000000004rem;
}
.dlzc {
  width: 3.75rem;
  height: 1.09rem;
  background: rgb(78, 82, 94);
  margin: 0 auto;
  display: flex;
  align-content: space-around;
  flex-wrap: wrap;
  justify-content: space-around;
}
.dlzc_a > span {
  display: inline-block;
  height: 0.35rem;
  line-height: 0.35rem;
  color: rgb(195, 198, 202);
  border: 1px solid rgb(66, 69, 77);
  background-color: rgb(85, 89, 101);
  padding: 0px 17px;
  border-radius: 6px;
  font-size: 14px;
}
.dlzc_b > span:nth-child(1) > img {
  width: 0.12rem;
  height: 0.12rem;
}

.dlzc_b:span:nth-child(2) {
  color: rgb(195, 198, 202);
}

.dlzc_b:span:nth-child(3) > a {
  color: rgb(195, 198, 202);
}
.footer {
  width: 1000px;
  height: 0.42rem;
  background-color: #ffffff;
  border-top: 1px solid #e7e7e7;
  border-bottom: 1px solid #f8f8f8;
  display: flex;
  position: relative;
}
.footer_sy {
  width: 60rem;
  height: 0.42rem;
  font-size: 0.1rem;
  margin: 0 auto;
  display: flex;
  justify-content: space-around;
  flex-direction: column;
  align-items: center;
}
#ss {
  color: #5d656b;
}
.footer_sy > p:nth-child(2) {
  color: #5d656b;
}
#hu {
  width: 50px;
  height: 50px;
  /* background: red; */
  border-radius: 50%;
  position: absolute;
  top: -100px;
  left: 300px;
  /* display: none; */
  opacity: 0.8;
}
#hu > a > img {
  width: 50px;
  height: 50px;
}
</style>