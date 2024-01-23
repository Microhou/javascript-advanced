# javascript-advanced
JavaScript advanced knowledge summary


https://www.codingnepalweb.com/create-glassmorphism-sidebar-html-css/


## 美团技术文档
https://tech.meituan.com/2022/10/13/dive-into-functional-programming-01.html

 box-sizing: content-box;
  /* Total width: 160px + (2 * 20px) + (2 * 8px) = 216px
     Total height: 80px + (2 * 20px) + (2 * 8px) = 136px
     Content box width: 160px
     Content box height: 80px */

 box-sizing: border-box;
  /* Total width: 160px
     Total height: 80px
     Content box width: 160px - (2 * 20px) - (2 * 8px) = 104px
     Content box height: 80px - (2 * 20px) - (2 * 8px) = 24px */

当 width: 100% and width: auto 的区别，
width: 100% 表示元素的宽度将会占据其父元素的宽度；
width: auto 表示元素的宽度将会根据其内容自动调整。
