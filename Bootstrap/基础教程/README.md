# Bootstrap 3 基础教程


.page-header 会显示一个 `下划线`

## 网格系统
  * col-xs-*    device-width < 768px
  * col-sm-*    device-width >= 768px
  * col-md-*    device-width >= 992px
  * col-lg-*    device-width >= 1200px  

 ```html
    <div class="container">
      <div class="row">
        <div class="col-md-8"></div>
        <div class="col-md-4"></div>
      </div>
    </div>
 ```

>[参考链接：https://tx321-4.github.io/study-bootstrap/基础教程/01.html](https://tx321-4.github.io/study-bootstrap/基础教程/01.html)

* 列的排序 -- 用来排序列的先后顺序
  * col-md-push-* 与 col-md-pull-* 

>[参考链接：https://tx321-4.github.io/study-bootstrap/基础教程/02.html](https://tx321-4.github.io/study-bootstrap/基础教程/02.html)

* 嵌套布局
>[参考链接：https://tx321-4.github.io/study-bootstrap/基础教程/03.html](https://tx321-4.github.io/study-bootstrap/基础教程/03.html)

* 偏移列
  * col-md-offset-*
>[参考链接：https://tx321-4.github.io/study-bootstrap/基础教程/04.html](https://tx321-4.github.io/study-bootstrap/基础教程/04.html)

* 显示与隐藏的响应式工具类
  * visible-* 
  * hidden-*
>[参考链接：https://tx321-4.github.io/study-bootstrap/基础教程/05.html](https://tx321-4.github.io/study-bootstrap/基础教程/05.html)

# 

## 导航栏
* 导航栏 
  * 夜间 navbar-inverse 
  * 默认 navbar-default
* 固定导航栏  
  * navbar-fixed-top 
  * navbar-fixed-bottom
  * navbar-static-top 随页面的滚动而滚动

>[参考链接：https://tx321-4.github.io/study-bootstrap/基础教程/06.html](https://tx321-4.github.io/study-bootstrap/基础教程/06.html)

* 响应式导航栏 
  * button data-target="#xxxx" data-toggle="collapse"
  * nav id="xxxx"

>[参考链接：https://tx321-4.github.io/study-bootstrap/基础教程/07.html](https://tx321-4.github.io/study-bootstrap/基础教程/07.html)

#

## 对话框
* 基本
  * modal-dialog
  * 布局 modal-header、modal-body、modal-footer
  * 大小 modal-sm、modal-lg
>[参考链接：https://tx321-4.github.io/study-bootstrap/基础教程/08.html](https://tx321-4.github.io/study-bootstrap/基础教程/08.html)
* 打开 
  * button data-toggle="modal" data-target="#login-modal"
  * div .modal #login-modal
* 关闭
  * button data-dismiss="modal"
* 打开过渡动画
  * div .modal.fade
>[参考链接：https://tx321-4.github.io/study-bootstrap/基础教程/09.html](https://tx321-4.github.io/study-bootstrap/基础教程/09.html)
* 暗色背景
  * data-backdrop = "false"
  * javascript: $(function(){$('#login-modal').modal(({show: false, backdrop: false}))})
* 调用同源页面
  * remote
* 方法
  * javascript: $("#login-modal").modal("show")
  * javascript: $("#login-modal").modal("hide")
  * javascript: $("#login-modal").modal("toggle")  
* 事件
  * show、shown、hide、hidden、loaded
  * javascript: $("#login-modal").on("show.bs.modal", function(){})  

#

## 幻灯片 carousel     
  * 基础 data-ride="carousel"
  * 左滑动 slide
  * 上一页，下一页 
    * a href="#slideshow" data-slide="prev" class="left carousel-control"
    * a href="#slideshow" data-slide="next" class="right carousel-control"
  * 圆点
    * li data-target="#slideshow" data-slide-to="0"

>[参考链接：https://tx321-4.github.io/study-bootstrap/基础教程/10.html](https://tx321-4.github.io/study-bootstrap/基础教程/10.html)
  