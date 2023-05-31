---网页设计规划---
网页布局：盒模型、表格、浮动
               定位布局（div+css）   分割16px
*响应式布局（适应移动端） 
flex弹性布局
容器属性：justify-content]
flex-start(默认 主轴前对齐）
flex-end（后对齐）
center（居中）
space-between（等距 首尾）
space-around(等距 两边)
space-evenly（等距 容器）
align-items
...
...
...

网页生成移动app（生成软件）


！！！
显示系统时间必须使用JavaScript，因为JavaScript是用于处理客户端的脚本语言，
可以实时获取系统时间并更新网页内容。在没有JavaScript的情况下，
无法直接从客户端获取系统时间。
那么只能做静态的时间


github、掘金、力扣、极客时间、51博客、csdn、openai、Notion、

学习借鉴/素材：
https://www.bilibili.com/video/BV1XJ411X7Ud/?p=63&vd_source=f1ae31e6ad7af9ba8857105fbf8a9597
https://www.bilibili.com/video/BV1Rv4y177rj/?spm_id_from=333.1007.tianma.2-1-3.click&vd_source=f1ae31e6ad7af9ba8857105fbf8a9597
https://www.bilibili.com/video/BV1Vv4y1p7mW/?share_source=copy_web&vd_source=951e4eb9968549c9388b035d6c119f61
http://www.huaibin.gov.cn/
https://pixso.cn/
openai.chatgpt
GitHub




适应IE浏览器

<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>适应IE浏览器的HTML网页</title>
  <style>
    /* 使用IE专用的CSS前缀 */
    .box {
      -ms-filter: "progid:DXImageTransform.Microsoft.gradient(startColorstr=#ffffff,endColorstr=#000000)";
      -ms-transform: rotate(45deg);
    }
  </style>
  <!--[if lt IE 9]>
  <script src="https://cdn.bootcss.com/html5shiv/3.7.3/html5shiv.min.js"></script>
  <script src="https://cdn.bootcss.com/respond.js/1.4.2/respond.min.js"></script>
  <![endif]-->
</head>
<body>
  <!-- 使用IE专用的HTML5标签 -->
  <!--[if lt IE 9]>
  <script>
    document.createElement('section');
    document.createElement('article');
    document.createElement('nav');
    document.createElement('header');
    document.createElement('footer');
  </script>
  <![endif]-->
  <section class="box">
    <h1>适应IE浏览器的HTML网页</h1>
    <p>这是一个适应IE浏览器的HTML网页示例。</p>
  </section>
  <!-- 使用IE专用的JavaScript代码 -->
  <!--[if lt IE 9]>
  <script>
    var xhr = new ActiveXObject('Microsoft.XMLHTTP');
    xhr.open('GET', 'data.txt', true);
    xhr.onreadystatechange = function () {
      if (xhr.readyState === 4 && xhr.status === 200) {
        console.log(xhr.responseText);
      }
    };
    xhr.send();
  </script>
  <![endif]-->
</body>
</html>










                                           --2023.05.12