

<style>
/* 去除通知栏 右上角 X */
 .notify-render .hope-close-button {
    display: none;
}



/* 此选项两处CSS 在v3.31.0中已优化 滚动显示 和 右下角设置网格模式尺寸大小 */
/* 文字超长自动换行 */
/*.name-box .name {
    white-space: unset !important;
    overflow: unset !important;
}*/
/* 缩略图图片变大 代码中的160px 自己改 现在是注释状态若需要自行解除注释 */
/*.obj-box > div {
grid-template-columns: repeat(auto-fill, minmax(160px, 1fr))
}
.obj-box > div .item-thumbnail{
  height: 100px;
}*/


/* 白天背景图 */
.hope-ui-light {
    background-image: url("https://orbit1024.top/wp-content/uploads/2025/05/1748364042-10001-scaled.jpg") !important;
    background-repeat: no-repeat;
    background-size: cover;
    background-attachment: fixed;
    background-position-x: center;
}

/* 夜间背景图 */
.hope-ui-dark {
    background-image: url("") !important;
    background-repeat: no-repeat;
    background-size: cover;
    background-attachment: fixed;
    background-position-x: center;
}

/* 手机端白天背景图 */
@media (max-width: 768px) {
    .hope-ui-light {
        background-image: url("") !important;
    }
}

/* 手机端夜间背景图 */
@media (max-width: 768px) {
    .hope-ui-dark {
        background-image: url("") !important;
    }
}

/*主列表白天模式透明*/
 .obj-box.hope-stack.hope-c-dhzjXW.hope-c-PJLV.hope-c-PJLV-igScBhH-css {
    background-color: rgba(255, 255, 255, 0.5) !important;
}
/*主列表夜间模式透明*/
 .obj-box.hope-stack.hope-c-dhzjXW.hope-c-PJLV.hope-c-PJLV-iigjoxS-css {
    background-color:rgb(0 0 0 / 50%) !important;
}
/*readme白天模式透明*/
 .hope-c-PJLV.hope-c-PJLV-ikSuVsl-css {
    background-color: rgba(255, 255, 255, 0.5) !important;
}
/*readme夜间模式透明*/
 .hope-c-PJLV.hope-c-PJLV-iiuDLME-css {
    background-color:rgb(0 0 0 / 50%) !important;
}

/*顶部右上角切换按钮透明*/
 .hope-ui-light .hope-c-ivMHWx-hZistB-cv.hope-icon-button {
    background-color: rgba(255, 255, 255, 0.5) !important;
}
.hope-ui-dark .hope-c-ivMHWx-hZistB-cv.hope-icon-button {
    background-color:rgb(0 0 0 / 50%) !important;
}

/*右下角侧边栏按钮透明 第一个是白天 第二个是夜间*/
 .hope-ui-light .hope-c-PJLV-ijgzmFG-css {
    background-color: rgba(255, 255, 255, 0.5) !important;
}
.hope-ui-dark .hope-c-PJLV-ijgzmFG-css {
    background-color:rgb(0 0 0 / 50%) !important;
}

/*白天模式代码块透明*/
 .hope-ui-light pre {
    background-color: rgba(255, 255, 255, 0.1)!important;
}
/*夜间模式代码块透明*/
 .hope-ui-dark pre {
    background-color: rgba(255, 255, 255, 0)!important;
}

/*左侧侧边栏目录*/
/*白天模式*/
 .hope-ui-light .hope-c-PJLV-ieGWMbI-css {
    background: rgba(255, 255, 255, 0) !important;
}
/*夜间模式*/
 .hope-ui-dark .hope-c-PJLV-ieGWMbI-css {
    background-color:rgb(0 0 0 / 0%) !important;
}

/* 返回顶部 */
 .hope-c-PJLV-ihVEsOa-css {
    background: rgba(255, 255, 255, 0) !important;
}
.hope-ui-dark .hope-c-PJLV-ihVEsOa-css {
    background-color:rgb(0 0 0 / 0%) !important;
}

/*正常情况未使用吸附功能*/
/*顶部*/
 .hope-c-PJLV-ikaMhsQ-css {
    background: rgba(255, 255, 255, 0) !important;
}
/*导航条*/ 
/*白天模式*/
 .hope-ui-light .hope-c-PJLV-idaeksS-css {
    background-color: rgba(255, 255, 255, 0) !important;
    border-radius: var(--hope-radii-xl) !important;
}
/*夜间模式*/
 .hope-ui-dark .hope-c-PJLV-idaeksS-css {
    background-color:rgb(0 0 0 / 0%) !important;
    border-radius: var(--hope-radii-xl) !important;
}
/* 吸附到页面顶部 */
/*顶部*/
 .hope-c-PJLV-icWrYmg-css {
    background: rgba(255, 255, 255, 0) !important;
}
/*导航条*/
 .hope-c-PJLV-icKsjdm-css::after {
    background: rgba(255, 255, 255, 0) !important;
}
/*白天模式*/
 .hope-ui-light .hope-c-PJLV-icKsjdm-css {
    background-color: rgba(255, 255, 255, 0) !important;
    border-radius: var(--hope-radii-xl) !important;
}
/*夜间模式*/
 .hope-ui-dark .hope-c-PJLV-icKsjdm-css {
    background-color:rgb(0 0 0 / 0%) !important;
    border-radius: var(--hope-radii-xl) !important;
}

/*仅吸附导航栏*/
/*导航条*/
 .hope-c-PJLV-ifdXShc-css::after {
    background: rgba(255, 255, 255, 0) !important;
}
/*白天模式*/
 .hope-ui-light .hope-c-hrsMRY {
    background-color: rgba(255, 255, 255, 0) !important;
    border-radius: var(--hope-radii-xl) !important;
}
/*夜间模式*/
 .hope-ui-dark .hope-c-hrsMRY {
    background-color:rgb(0 0 0 / 0%) !important;
    border-radius: var(--hope-radii-xl) !important;
}
/*全局字体*/

 * {
   font-family:LXGW WenKai
   }
* {
  font-weight:bold
  }
  body {
  font-family: LXGW WenKai;
  }

</style>




放到自定义头部中
