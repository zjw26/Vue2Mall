<template>
<div>
    <svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" style="position: absolute; width: 0px; height: 0px; overflow: hidden;"><defs><symbol id="icon-add" viewBox="0 0 32 32"><title>add2</title> <path d="M15 17h-13.664c-0.554 0-1.002-0.446-1.002-1 0-0.552 0.452-1 1.002-1h13.664v-13.664c0-0.554 0.446-1.002 1-1.002 0.552 0 1 0.452 1 1.002v13.664h13.664c0.554 0 1.002 0.446 1.002 1 0 0.552-0.452 1-1.002 1h-13.664v13.664c0 0.554-0.446 1.002-1 1.002-0.552 0-1-0.452-1-1.002v-13.664z" class="path1"></path></symbol> <symbol id="icon-ok" viewBox="0 0 32 32"><title>ok</title> <path d="M31.020 0.438c-0.512-0.363-1.135-0.507-1.757-0.406s-1.166 0.435-1.529 0.937l-17.965 24.679-5.753-5.67c-0.445-0.438-1.035-0.679-1.664-0.679s-1.219 0.241-1.664 0.679c-0.917 0.904-0.917 2.375 0 3.279l7.712 7.6c0.438 0.432 1.045 0.681 1.665 0.681l0.195-0.008c0.688-0.057 1.314-0.406 1.717-0.959l19.582-26.9c0.754-1.038 0.512-2.488-0.538-3.233z" class="path1"></path></symbol> <symbol id="icon-edit" viewBox="0 0 32 32"><title>edit</title> <path d="M28.287 8.51l-4.805-4.806 0.831-0.831c0.472-0.472 1.086-0.777 1.564-0.777 0.248 0 0.452 0.082 0.622 0.253l3.143 3.144c0.539 0.54 0.133 1.529-0.524 2.186l-0.831 0.831zM26.805 9.992l-1.138 1.138-4.805-4.806 1.138-1.138 4.805 4.806zM24.186 12.612l-14.758 14.762-4.805-4.806 14.758-14.762 4.805 4.806zM7.379 28.288l-4.892 1.224 1.223-4.894 3.669 3.67zM31.123 4.011l-3.143-3.144c-0.567-0.567-1.294-0.867-2.103-0.867-1.036 0-2.174 0.52-3.045 1.391l-20.429 20.436c-0.135 0.134-0.23 0.302-0.276 0.487l-2.095 8.385c-0.089 0.355 0.017 0.736 0.276 0.995 0.198 0.198 0.461 0.307 0.741 0.307 0.085 0 0.171-0.010 0.254-0.031l8.381-2.096c0.185-0.047 0.354-0.142 0.487-0.276l20.43-20.436c1.409-1.41 2.042-3.632 0.524-5.15v0z" class="path1"></path></symbol> <symbol id="icon-del" viewBox="0 0 32 32"><title>delete</title> <path d="M11.355 4.129v-2.065h9.29v2.065h-9.29zM6.194 29.935v-23.742h19.613v23.742h-19.613zM30.968 4.129h-8.258v-3.097c0-0.569-0.463-1.032-1.032-1.032h-11.355c-0.569 0-1.032 0.463-1.032 1.032v3.097h-8.258c-0.569 0-1.032 0.463-1.032 1.032s0.463 1.032 1.032 1.032h3.097v24.774c0 0.569 0.463 1.032 1.032 1.032h21.677c0.569 0 1.032-0.463 1.032-1.032v-24.774h3.097c0.569 0 1.032-0.463 1.032-1.032s-0.463-1.032-1.032-1.032v0z" class="path1"></path> <path d="M10.323 9.806c-0.569 0-1.032 0.463-1.032 1.032v14.452c0 0.569 0.463 1.032 1.032 1.032s1.032-0.463 1.032-1.032v-14.452c0-0.569-0.463-1.032-1.032-1.032z" class="path2"></path> <path d="M16 9.806c-0.569 0-1.032 0.463-1.032 1.032v14.452c0 0.569 0.463 1.032 1.032 1.032s1.032-0.463 1.032-1.032v-14.452c0-0.569-0.463-1.032-1.032-1.032z" class="path3"></path> <path d="M21.677 9.806c-0.569 0-1.032 0.463-1.032 1.032v14.452c0 0.569 0.463 1.032 1.032 1.032s1.032-0.463 1.032-1.032v-14.452c0-0.569-0.463-1.032-1.032-1.032z" class="path4"></path></symbol> <symbol id="icon-clock" viewBox="0 0 32 32"><title>clock</title> <path fill="#605f5f" d="M16 29c-7.168 0-13-5.831-13-13s5.832-13 13-13c7.168 0 13 5.832 13 13s-5.832 13-13 13zM16 0c-8.822 0-16 7.178-16 16s7.178 16 16 16c8.822 0 16-7.178 16-16s-7.178-16-16-16z" class="path1"></path> <path fill="#605f5f" d="M23.958 21.837l-6.958-6.489v-6.282c0-0.827-0.673-1.5-1.5-1.5s-1.5 0.673-1.5 1.5v6.934c0 0.414 0.174 0.814 0.477 1.098l7.435 6.934c0.279 0.259 0.642 0.402 1.023 0.402 0.415 0 0.814-0.174 1.096-0.477 0.564-0.605 0.532-1.555-0.073-2.12z" class="path2"></path></symbol></defs></svg>
    <nav-header v-on:login="init()" v-on:logout="init()"></nav-header>
    <nav-bread>
        <span>MyCart</span>
    </nav-bread>
    <div class="container">
    <div class="cart">
        <div class="page-title-normal" style="text-align:left;">
        <h2 class="page-title-h2"><span>My Cart</span></h2>
        </div>
        <div class="item-list-wrap">
        <div class="cart-item">
            <div class="cart-item-head">
            <ul>
                <li>Items</li>
                <li>Price</li>
                <li>Quantity</li>
                <li>Subtotal</li>
                <li>Edit</li>
            </ul>
            </div>
            <ul class="cart-item-list">
            <li v-for="(item,index) in cartList">
                <div class="cart-tab-1">
                <div class="cart-item-check">
                    <a href="javascipt:;" class="checkbox-btn item-check-btn" v-bind:class="{'check':item.checked=='1'}" @click="check(item)">
                    <svg class="icon icon-ok">
                        <use xlink:href="#icon-ok"></use>
                    </svg>
                    </a>
                </div>
                <div class="cart-item-pic">
                    <img v-bind:src="'static/'+item.productImage">
                </div>
                <div class="cart-item-title">
                    <div class="item-name">{{item.productName}}</div>
                </div>
                </div>
                <div class="cart-tab-2">
                <div class="item-price">{{item.salePrice | currency('￥')}}</div>
                </div>
                <div class="cart-tab-3">
                <div class="item-quantity">
                    <div class="select-self select-self-open">
                        <div class="select-self-area">
                            <span class="input-sub" @click="del(index)">-</span> 
                            <span class="select-ipt">{{item.productNum}}</span> 
                            <span class="input-add" @click="add(index)">+</span>
                        </div>
                    </div>
                </div>
                </div>
                <div class="cart-tab-4">
                <div class="item-price-total">{{item.productNum*item.salePrice | currency('￥')}}</div>
                </div>
                <div class="cart-tab-5">
                <div class="cart-item-opration" @click="delConfirm(item.productId)">
                    <a href="javascript:;" class="item-edit-btn">
                    <svg class="icon icon-del">
                        <use xlink:href="#icon-del"></use>
                    </svg>
                    </a>
                </div>
                </div>
            </li>
            </ul>
        </div>
        </div>
        <div class="cart-foot-wrap">
        <div class="cart-foot-inner">
            <div class="cart-foot-l">
            <div class="item-all-check" @click="checkAll">
                <a href="javascipt:;" >
                    <span class="checkbox-btn item-check-btn" v-bind:class="{'check':isCheckAll}">
                        <svg class="icon icon-ok"><use xlink:href="#icon-ok"/></svg>
                    </span>
                <span>Select all</span>
                </a>
            </div>
            </div>
            <div class="cart-foot-r">
            <div class="item-total">
                Item total: <span class="total-price">{{allPrice | currency('￥')}}</span>
            </div>
            <div class="btn-wrap">
                <a class="btn btn--red" v-bind:class="{'btn--dis': allPrice==0}" @click="checkout">Checkout</a>
            </div>
            </div>
        </div>
        </div>
    </div>
    </div>
    <modal v-bind:mdShow="mdShow" v-on:close="closeModal()">
        <p slot="message">
            你确认要删除该条数据吗？
        </p>
        <div slot="btnGroup">
            <a class="btn btn--m" href="javascript:" @click="delCart()">确定</a>
            <a class="btn btn--m" href="javascript:">取消</a>
        </div>
    </modal>
    <nav-footer></nav-footer>
</div>

</template>
<style>
.select-self-area {
    width: auto;
    background: #f0f0f0;
    border-radius: 3px;
    min-width: 50px;
    max-width: 240px;
    height: 30px;
    line-height: 30px;
}
.input-add, .input-sub {
    min-width: 40px;
    height: 100%;
    border: 0;
    color: #605f5f;
    text-align: center;
    font-size: 16px;
    overflow: hidden;
    display: inline-block;
    background: #f0f0f0;
}
.item-quantity .select-self-area .select-ipt {
    display: inline-block;
    padding: 0 3px;
    width: 30px;
    min-width: 30px;
    text-align: center;
}

.item-quantity .select-self-area {
    background: none;
    border: 1px solid #f0f0f0;
}

</style>

<script>
import './../assets/css/checkout.css'
import NavHeader from './../components/header'
import NavFooter from './../components/footer'
import NavBread from './../components/bread'
import Modal from './../components/modal'
import {currency} from './../util/currency.js'
import axios from 'axios'
export default {
  name: 'HelloWorld',
  data () {
    return {
      cartList:'',
      mdShow:false,
      productId:'',
      isCheckAll:false
    }
  },
  components:{
      NavHeader,
      NavFooter,
      NavBread,
      Modal
  },
  mounted:function(){  
    this.init();
  },
  filters:{
      currency:currency
  },
  computed:{
      allPrice(){
          console.log(this)
          var allPrice = 0;
          this.cartList.forEach((item)=>{
              if(item.checked == '1'){
                  allPrice += item.salePrice*item.productNum;
              }
          })
          return allPrice;
      }
  },
//   updated:function(){
//       console.log('update')
//     var checkAll = true;
//     this.cartList.forEach((item)=>{
//         if(item.checked != '1'){
//             checkAll = false;
//         }
//     })
//     this.isCheckAll = checkAll;
//   },
  watch:{
      'cartList':{
          handler:function(newVal,oldVal){
              console.log(newVal)
            var checkAll = true;
            newVal.forEach((item)=>{
                if(item.checked != '1'){
                    checkAll = false;
                }
            })
            this.isCheckAll = checkAll;
          },
          deep:true
      }
      
  },
  methods:{
      init(){
          let _this = this;
          axios.get('/users/cartList').then((response)=>{
              let res = response.data;
              _this.cartList = res.result;
          })
      },
      del(index){
          let _this = this;
          axios.post('/users/reduce',{
              productId:_this.cartList[index].productId
          }).then((response)=>{
              let res = response.data;
              if(res.status == '0'){
                  _this.cartList[index].productNum--;
                  this.$store.commit('updateCartCount',-1);
                  if(_this.cartList[index].productNum == 0){
                      _this.init();
                  }
              }
          })
      },
      add(index){
          let _this = this;
          axios.post('/users/add',{
              productId:_this.cartList[index].productId
          }).then((response)=>{
              let res = response.data;
              if(res.status == '0'){
                  _this.cartList[index].productNum++;
                  this.$store.commit('updateCartCount',1);
              }
          })
      },
      closeModal(){
          this.mdShow = false;
      },
      delConfirm(productId){
          this.mdShow = true;
          this.productId = productId;
          console.log(productId)
      },
      delCart(){
          let _this = this;
          axios.post('/users/cartDel',{
              productId:_this.productId
          }).then((response)=>{
              let res = response.data;
              let count = 0;
              if(res.status == '0'){
                  this.cartList.forEach(item=>{
                      if(item.productId == _this.productId){
                          count += item.productNum;
                      }
                  })
                  _this.closeModal();
                  _this.init();
                  this.$store.commit('updateCartCount',-count);
              }
          })
      },
      check(item){
          let _this = this;
          axios.post('/users/checked',{
              productId:item.productId
          }).then((response)=>{
              let res = response.data;
              if(res.status == '0'){
                if(item.checked == '1'){
                    item.checked = '0'
                }else if(item.checked == '0'){
                    item.checked = '1';
                }
              }
          })
      },
      checkAll(){
          let _this = this;
          _this.isCheckAll = !_this.isCheckAll;
          if(_this.isCheckAll){
              _this.cartList.forEach((item)=>{
                  item.checked = '1';
              })
          }else{
              _this.cartList.forEach((item)=>{
                  item.checked = '0';
              })
          }
          axios.post('/users/checkAll',{checkAll:_this.isCheckAll})
          .then((response)=>{
              let res = response.data;
              if(res.status == '0'){
                if(_this.isCheckAll){
                _this.cartList.forEach((item)=>{
                    item.checked = '1';
                })
                }else{
                    _this.cartList.forEach((item)=>{
                        item.checked = '0';
                    })
                }
              }
          })
       },
       checkout(){
           let _this = this;
           if(_this.allPrice > 0){
               this.$router.push({
                   path:'/address'
               })
           }
       }
      
  }
}
</script>