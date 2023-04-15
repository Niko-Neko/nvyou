<template>
  <div class="login-container padding-l-r-32 fz-14">
    <div class="head">
        <div class="logobox center">
            <img class="img-auto " src="../../assets/img/图片 Copy@2x.png" alt="">
        </div>
        <center class="dec">欢迎你到来</center>
    </div>
    <div class="main">
        <div class="form">
            <div class="user">
                <input type="text" placeholder="用户名">
                <img src="../../assets/img/md-person Copy@2x.png" alt="">          
                </div>
                
            <div  class="passwords">
                <input type="text" placeholder="密码">
                <img src="../../assets/img/md-lock Copy@2x.png" alt="">
            </div>
                <div class="operate">
                    <span>手机验证码登录</span>
                    <span>忘记密码</span>
                </div>
                <div class="login_reg">
                    <div class="loginbtn">登录</div>
                    <div class="regbtn">注册</div>
                </div>
                <div class="dsf">
                    <div class="dec">第三方登录</div>
                        <div class="decicon">
                            <div><img src="../../assets/img/fab fa-qq Copy@2x.png" alt=""></div>
                            <div><img src="../../assets/img/antOutline-wechat Copy@2x (1).png" alt=""></div>
                            <div><img src="../../assets/img/fab fa-weibo Copy@2x (1).png" alt=""></div>
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
            .user,.passwords{
                position: relative;
                img{
                    position: absolute;
                    left: 18px;
                    top: 50%;
                    width: 24px;
                    height: 24px;
                    transform: translateY(-50%);
                }
            }
               input{
                padding-left:56px;
                height: 42px;
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
                div{
                    width: 130px;
                    color:white;
                    height: 38px;
                    text-align: center;
                    line-height: 38px;
                    border-radius:6px ;
                }
                .loginbtn{
                    background-color: rgba(189, 192, 200, 1);
                }
                .regbtn{
                    background-color: rgba(113, 148, 255, 1);
                }
            }
            .dsf{
                .decicon{
                    div{
                        width: 24px;
                        height: 24px;
                        img{
                            width: 100%;
                        }
                    }
                    padding: 21px 24px;
                    display: flex;
                    justify-content: space-between;
                }
            }
        }
    }
    .foot{}
}
</style>