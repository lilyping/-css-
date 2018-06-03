# -css-

纯css绘制的空心三角形（登录页面）

效果图

![Alt text](https://github.com/lilyping/-css-/blob/master/bgTrigger/imgs/%E6%95%88%E6%9E%9C%E5%9B%BE.png)


部分源代码

/*空心三角形 before/after伪类*/
.bgIcon #trigger {
    width:3.9rem;
    height:2.9rem;
     -webkit-border-radius:.12rem;
     border-radius: .12rem;
     /*border: 1px #808080 solid;*/
     background-color: #6a70a4;
    opacity: .2;
    position: relative;
    top:50%;
    left:50%;
    margin-left: -1.95rem;
    margin-top: -1.45rem;
    box-shadow: .03rem .03rem .04rem #000;
    -webkit-box-shadow: .03rem .03rem .04rem #000;
    border: .01rem solid #fff;
     }

#trigger:before {
      content: " ";
     position: absolute;
      bottom: 99%;
      left:45%;
      /*left: .5rem;*/
      width: 0;
      height: 0;
      border-left: .24rem solid transparent;
      border-bottom: .24rem solid #6a70a4;
      border-right: .24rem solid transparent;
      opacity: .5;
     }

#trigger:after {
      content: " ";
      position: absolute;
      bottom:99%;
      left:46%;
      /*left: .51rem;*/
      width: 0;
     height: 0;
     border-left: .23rem solid transparent;
     border-bottom: .23rem solid #fff;
     border-right: .23rem solid transparent;
      .}

