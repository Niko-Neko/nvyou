<template>
  <div class="login-container padding-l-r-32 fz-14">
    <div class="head">
        <div class="logobox center">
            <img class="img-auto " src="../../assets/img/图片 Copy@2x.png" alt="">
        </div>
        <center class="dec">欢迎你到来</center>
    </div>
    <div class="main ">
        <div class="form">
                <input type="text">
                <input type="text">
                <div class="operate">
                    <span>手机验证码登录</span>
                    <span>忘记密码</span>
                </div>
                <div class="login_reg">
                    <van-button type="primary" round>登录</van-button>
                    <van-button type="danger" round>注册</van-button>
                </div>
                <div class="dsf">
                    <div class="dec">第三方登录</div>
                        <div class="decicon">
                            
                        </div>
                </div>
        </div>
    </div>
  </div>
</template>
<script>
export default {
  components: {},
  name: "login",
  props: [],
  data() {
    return {};
  },
  methods: {},
  computed: {},
  watch: {},
  created() {},
  mounted() {},
   
};
</script>
<style lang='less' scpoed>
.login-container{
    padding-top: 42px;
    .head{
        .logobox{
        width: 134px;
        height: 144px;
        }
        .dec{
            padding: 14px 0 54px 0;
        }
    }
    .main{
        .form{
            display: flex;
            flex-direction: column;
            justify-content: center;
            gap: 18px;
            input{
                height: 45px;
                border-radius: 5px 5px 5px 5px;
                width: 100%;
                border: 1px solid rgba(187, 187, 187, 1);
            }
            .operate{
                display: flex;
                justify-content: space-between;
                align-items: center;
            }
            .login_reg{
                display: flex;
                justify-content: space-between;
                align-items: center;
            }
            .dsf{}
        }
    }
    .foot{}
}
</style>