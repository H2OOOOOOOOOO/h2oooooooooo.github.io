<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>人工智能与计算机学院 - 访企拓岗专项行动</title>
    <style>
        /* 基础样式重置与布局 */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: "Microsoft YaHei", "Segoe UI", sans-serif;
        }
        body {
            line-height: 1.6;
            color: #333;
            background-color: #f9f9f9;
        }
        a {
            color: #0066cc;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .clearfix::after {
            content: "";
            display: block;
            clear: both;
        }
        .container {
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 15px;
        }

        /* 头部与导航 */
        .header {
            background-color: #fff;
            border-bottom: 1px solid #eee;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
        }
        .header-top {
            padding: 15px 0;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .logo {
            display: block;
        }
        .logo img {
            height: 60px;
            width: auto;
        }
        .main-nav {
            position: relative;
        }
        .nav-list {
            display: flex;
            list-style: none;
        }
        .nav-list > li {
            position: relative;
            padding: 0 15px;
        }
        .nav-list > li > a {
            display: block;
            padding: 10px 5px;
            font-size: 16px;
            color: #333;
            font-weight: 500;
            white-space: nowrap;
        }
        .nav-list > li > a:hover {
            color: #0066cc;
        }
        .sub-menu {
            display: none;
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 180px;
            background-color: #fff;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            border: 1px solid #ddd;
            z-index: 1000;
            list-style: none;
        }
        .sub-menu li {
            border-bottom: 1px solid #f0f0f0;
        }
        .sub-menu li:last-child {
            border-bottom: none;
        }
        .sub-menu a {
            display: block;
            padding: 10px 15px;
            font-size: 14px;
            color: #555;
        }
        .sub-menu a:hover {
            background-color: #f5f5f5;
            color: #0066cc;
        }
        .nav-list > li:hover .sub-menu {
            display: block;
        }

        /* 横幅 */
        .banner {
            width: 100%;
            overflow: hidden;
            background-color: #f0f0f0;
            text-align: center;
        }
        .banner img {
            max-width: 100%;
            height: auto;
            display: block;
        }

        /* 主体内容 */
        .content-wrapper {
            display: flex;
            margin: 30px 0;
        }
        .sidebar {
            width: 25%;
            padding-right: 30px;
        }
        .sidebar h2 {
            font-size: 20px;
            color: #0066cc;
            padding-bottom: 10px;
            margin-bottom: 20px;
            border-bottom: 2px solid #0066cc;
        }
        .side-menu {
            background-color: #fff;
            border: 1px solid #ddd;
        }
        .side-menu ul {
            list-style: none;
        }
        .side-menu li {
            border-bottom: 1px solid #eee;
        }
        .side-menu li:last-child {
            border-bottom: none;
        }
        .side-menu a {
            display: block;
            padding: 12px 20px;
            font-size: 15px;
            color: #333;
        }
        .side-menu a:hover {
            background-color: #f5f9ff;
            color: #0066cc;
        }
        .main-content {
            width: 75%;
            background-color: #fff;
            padding: 30px;
            border: 1px solid #eee;
            box-shadow: 0 2px 8px rgba(0,0,0,0.05);
        }
        .breadcrumb {
            font-size: 14px;
            color: #666;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 1px dashed #ddd;
        }
        .breadcrumb a {
            color: #666;
        }
        .breadcrumb span {
            color: #999;
        }
        .article-title {
            font-size: 28px;
            font-weight: bold;
            text-align: center;
            margin-bottom: 20px;
            color: #222;
            line-height: 1.4;
        }
        .article-meta {
            text-align: center;
            color: #888;
            font-size: 14px;
            margin-bottom: 30px;
            padding-bottom: 20px;
            border-bottom: 1px solid #eee;
        }
        .article-body {
            font-size: 16px;
            line-height: 1.8;
        }
        .article-body p {
            margin-bottom: 20px;
            text-indent: 2em;
        }
        .article-body img {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 20px auto;
            border: 1px solid #ddd;
        }
        .img-caption {
            text-align: center;
            font-size: 14px;
            color: #666;
            font-style: italic;
            margin-top: -10px;
            margin-bottom: 30px;
        }
        .article-nav {
            margin-top: 40px;
            padding-top: 20px;
            border-top: 1px solid #eee;
        }
        .article-nav a {
            display: block;
            padding: 10px 0;
            font-size: 15px;
        }

        /* 页脚 */
        .footer {
            background-color: #2c3e50;
            color: #ecf0f1;
            padding: 40px 0 20px;
            margin-top: 50px;
        }
        .footer-content {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
        }
        .footer-section {
            flex: 1;
            min-width: 300px;
            margin-bottom: 20px;
            padding: 0 20px;
        }
        .footer-logo img {
            height: 50px;
            margin-bottom: 15px;
        }
        .footer-text {
            font-size: 13px;
            line-height: 1.6;
            color: #bdc3c7;
        }
        .footer-text a {
            color: #bdc3c7;
        }
        .footer-text a:hover {
            color: #fff;
        }
        .footer-contact p {
            margin-bottom: 8px;
        }
        .footer-bottom {
            text-align: center;
            margin-top: 30px;
            padding-top: 20px;
            border-top: 1px solid #3a506b;
            font-size: 13px;
            color: #95a5a6;
        }
        .footer-bottom a {
            color: #95a5a6;
        }

        /* 响应式 */
        @media (max-width: 992px) {
            .content-wrapper {
                flex-direction: column;
            }
            .sidebar, .main-content {
                width: 100%;
            }
            .sidebar {
                padding-right: 0;
                margin-bottom: 30px;
            }
            .nav-list {
                flex-wrap: wrap;
            }
            .nav-list > li {
                padding: 5px 10px;
            }
        }
        @media (max-width: 768px) {
            .header-top {
                flex-direction: column;
                align-items: flex-start;
            }
            .main-nav {
                width: 100%;
                margin-top: 15px;
            }
            .nav-list {
                flex-direction: column;
            }
            .sub-menu {
                position: static;
                box-shadow: none;
                border: none;
                padding-left: 20px;
            }
        }
    </style>
</head>
<body>
    <!-- 头部导航 -->
    <header class="header">
        <div class="container">
            <div class="header-top clearfix">
                <a href="../../index.htm" class="logo">
                    <img src="../../images/3logo20250804.png" alt="学院Logo">
                </a>
                <nav class="main-nav">
                    <ul class="nav-list">
                        <li><a href="../../index.htm">网站首页</a></li>
                        <li>
                            <a href="../../xygk1/xyjj.htm">学院概况</a>
                            <ul class="sub-menu">
                                <li><a href="../../xygk1/xyjj.htm">学院简介</a></li>
                                <li><a href="../../xygk1/xyld.htm">学院领导</a></li>
                                <li><a href="../../xygk1/nsjg.htm">内设机构</a></li>
                                <li><a href="../../xygk1/yzxx.htm">院长信箱</a></li>
                            </ul>
                        </li>
                        <li>
                            <a href="../../list.jsp?urltype=tree.TreeTempUrl&wbtreeid=1104">学院动态</a>
                            <ul class="sub-menu">
                                <li><a href="../../list.jsp?urltype=tree.TreeTempUrl&wbtreeid=1104">通知公告</a></li>
                                <li><a href="../../list.jsp?urltype=tree.TreeTempUrl&wbtreeid=1103">学院新闻</a></li>
                                <li><a href="../../list.jsp?urltype=tree.TreeTempUrl&wbtreeid=1102">讲座报告</a></li>
                            </ul>
                        </li>
                        <li>
                            <a href="../../szdw1/j_____s1.htm">师资队伍</a>
                            <ul class="sub-menu">
                                <li><a href="../../szdw1/j_____s1.htm">教 授</a></li>
                                <li><a href="../../szdw1/fjs.htm">副教授</a></li>
                                <li><a href="../../szdw1/js.htm">讲师</a></li>
                                <li><a href="../../szdw1/jpds.htm">兼聘导师</a></li>
                                <li><a href="../../szdw1/szzp.htm">师资招聘</a></li>
                            </ul>
                        </li>
                        <li><a href="#">人才培养</a></li>
                        <li><a href="../../list.jsp?urltype=tree.TreeTempUrl&wbtreeid=1032">科学研究</a></li>
                        <li><a href="../../list.jsp?urltype=tree.TreeTempUrl&wbtreeid=1036">党的建设</a></li>
                        <li><a href="../../list.jsp?urltype=tree.TreeTempUrl&wbtreeid=1039">学生天地</a></li>
                        <li><a href="../../English/Introduction.htm">English</a></li>
                    </ul>
                </nav>
            </div>
        </div>
    </header>

    <!-- 横幅图片 (为示例保留占位，实际使用时替换src) -->
    <div class="banner">
        <img src="../../images/banner-ber.jpg" alt="横幅">
    </div>

    <!-- 主内容区 -->
    <div class="container content-wrapper">
        <!-- 左侧边栏 -->
        <aside class="sidebar">
            <h2>网站首页</h2>
            <div class="side-menu">
                <ul>
                    <!-- 侧边栏导航链接示例，可根据实际需要修改 -->
                    <li><a href="../../list.jsp?urltype=tree.TreeTempUrl&wbtreeid=1104">学院新闻</a></li>
                    <li><a href="../../list.jsp?urltype=tree.TreeTempUrl&wbtreeid=1103">通知公告</a></li>
                    <li><a href="../../list.jsp?urltype=tree.TreeTempUrl&wbtreeid=1102">讲座报告</a></li>
                    <li><a href="../../xygk1/xyjj.htm">学院简介</a></li>
                    <li><a href="../../szdw1/j_____s1.htm">师资队伍</a></li>
                </ul>
            </div>
        </aside>

        <!-- 右侧主内容 -->
        <main class="main-content">
            <!-- 面包屑导航 -->
            <div class="breadcrumb">
                <a href="../../index.htm">网站首页</a> &gt;
                <a href="../../list.jsp?urltype=tree.TreeTempUrl&wbtreeid=1054">学院新闻</a> &gt;
                <span>正文</span>
            </div>

            <!-- 文章标题 -->
            <h1 class="article-title">人工智能与计算机学院赴苏州开展“访企拓岗促就业”专项行动</h1>

            <!-- 文章元信息 -->
            <div class="article-meta">
                日期：2026-03-25 &nbsp;&nbsp; 点击数：0 &nbsp;&nbsp; 人工智能与计算机学院 &nbsp; 文：米宁；图：高嘉婧；审核：王莉莉
            </div>

            <!-- 文章正文 -->
            <div class="article-body">
                <p>为深入贯彻落实教育部及学校“访企拓岗促就业”专项工作部署，进一步深化校企合作，精准对接企业人才需求，3月24日，江南大学人工智能与计算机学院党委副书记、副院长王莉莉，辅导员米宁及2026届、2027届本研学生代表赴中科可控信息产业有限公司、华启智能科技股份有限公司开展“访企拓岗促就业”专项行动。</p>
                <p>在中科可控信息产业有限公司，学院一行参观了企业展厅，了解公司发展历程、核心业务、技术研发成果及未来发展规划，让师生对信息技术产业发展趋势有了更直观的认识。座谈中，中科可控基础软件部研发经理亢曼曼、硬件技术部研发经理沙祥彪结合部门职责、岗位设置及技术要求等方面作详细解答，人力资源部人力资源经理罗兴安介绍了企业招聘标准及职业发展路径。王莉莉介绍了学院学科建设、人才培养特色及毕业生就业基本情况，希望双方以此次走访为契机，深化在人才招聘、实习实训、项目合作等方面的协同，实现校企资源共享、优势互补。2026届签约学生、2027届毕业生在会上与企业方作了充分提问交流。</p>
                <p>在华启智能科技股份有限公司，学院一行在企业负责人陪同下参观了展厅，了解公司在安全监测系统、智能设备研发等领域的产品优势及应用场景。座谈环节，华启智能党支部副书记、副总经理陈皓，总经理助理兼技术总监韩强，总经理助理兼研究院院长郑霄峰结合自身工作经历和业务与师生展开深入交流；人力资源部副经理谢理波介绍了公司发展布局、技术研发方向及人才需求，解读了人工智能、软件开发等相关岗位的能力要求。王莉莉就学院人才培养方案优化、学生实践能力提升等与企业深入探讨。与会学生积极发言，围绕岗位招聘、职业发展、技能提升等问题与企业负责人互动提问，现场交流氛围热烈，拉近了学生与企业的距离。</p>
                <p>此次专项行动不仅精准掌握了两家企业的人才需求导向，拓宽了毕业生就业渠道，还为学院优化人才培养方案、深化产教融合提供了参考。下一步，学院将持续常态化开展访企拓岗行动，加强与优质企业的深度合作，切实把走访成果转化为就业实效，全力护航毕业生高质量就业。</p>

                <img src="/__local/B/99/FC/765BC902FB70EEBF28842CD3C8F_5F549BA3_16649.jpg" alt="参观企业展厅">
                <p class="img-caption">参观企业展厅</p>

                <img src="/__local/9/88/51/4BE23D3EECF480F95D0D51C54B3_E8D54D68_16C92.jpg" alt="与中科可控座谈交流">
                <p class="img-caption">与中科可控座谈交流</p>

                <img src="/__local/4/D3/8D/165A0C550970FEA327331F7906C_FDEB6E02_1D6F9.jpg" alt="与华启智能座谈交流">
                <p class="img-caption">与华启智能座谈交流</p>

                <img src="/__local/F/46/75/9FDABC17E558BC94D2831342EF1_392E4A6A_23E21.jpg" alt="与中科可控合影">
                <p class="img-caption">与中科可控合影</p>

                <img src="/__local/6/69/A0/FC8133F5D14BDF44F8FBBE71251_BF211718_182EC.jpg" alt="与华启智能合影">
                <p class="img-caption">与华启智能合影</p>
            </div>

            <!-- 下一篇导航 -->
            <div class="article-nav">
                <a href="4617.htm">下一篇：江苏第二师范学院来访</a>
            </div>
        </main>
    </div>

    <!-- 页脚 -->
    <footer class="footer">
        <div class="container">
            <div class="footer-content">
                <div class="footer-section">
                    <div class="footer-logo">
                        <!-- 此处为版权或技术支持单位Logo，示例保留占位 -->
                        <img src="/__local/9/C5/CF/CE23AA0F351DEE50CFD74AD015C_8F6035A5_95A8.png" alt="技术支持单位">
                    </div>
                    <p class="footer-text">
                        技术支持：<a href="" target="_blank">信息化建设管理处</a><br>
                        校内备案号：JW备170150
                    </p>
                </div>
                <div class="footer-section footer-contact">
                    <p class="footer-text">
                        地址：江苏省无锡市蠡湖大道1800号<br>
                        邮编：214122<br>
                        联系电话：0510-85327307<br>
                        服务邮箱：rgznxy@
                    </p>
                </div>
                <!-- 可在此处添加二维码或其他信息 -->
                <div class="footer-section" style="text-align: center;">
                    <!-- 示例二维码占位图 -->
                    <img src="/__local/C/27/66/EF8019B754588CD4B7A4B1DE236_77FB1CFF_588E.png" alt="二维码" style="max-height: 100px;">
                </div>
            </div>
            <div class="footer-bottom">
                <!-- 版权年份可动态生成 -->
                <p>© 2026 江南大学人工智能与计算机学院. 保留所有权利.</p>
            </div>
        </div>
    </footer>

    <!-- 核心交互脚本 (已移除所有追踪和广告脚本，仅保留必要的导航交互) -->
    <script>
        // 简单的导航菜单悬停效果
        document.addEventListener('DOMContentLoaded', function() {
            const navItems = document.querySelectorAll('.nav-list > li');
            navItems.forEach(item => {
                item.addEventListener('mouseenter', function() {
                    const subMenu = this.querySelector('.sub-menu');
                    if (subMenu) {
                        subMenu.style.display = 'block';
                    }
                });
                item.addEventListener('mouseleave', function() {
                    const subMenu = this.querySelector('.sub-menu');
                    if (subMenu) {
                        subMenu.style.display = 'none';
                    }
                });
            });
        });
    </script>
</body>
</html>
