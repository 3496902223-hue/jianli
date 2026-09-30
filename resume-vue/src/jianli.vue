<template>
    <div class="resume-page">
      <div class="resume-container">
  
        <!-- 顶部个人信息 -->
        <header class="resume-header">
          <h1 class="resume-name">魏毅</h1>
          <div class="resume-contact">
            <strong>
                <span>18104088897 </span>
                <span>|</span>
                <span>3496902223@qq.com </span>
                <span>|</span>
             <span>大连</span>
            </strong>
          </div>
          <div class="resume-meta">
            <strong>
                <span>男 | 03年 | 本科 | 26年毕业生</span>
                <span> </span>
                <span class="resume-job">Java全栈开发方向 | 应聘：初级软件工程师</span>
            </strong>
          </div>
          <p class="resume-summary">
            2026届软件工程应届生，具备SpringBoot+Vue前后端分离项目实战经验；学习接受能力强，能够快速上手新框架与开发工具，遇到问题自主查阅资料排查解决，乐于接触新技术，期望从事初级开发岗位，踏实完成业务开发工作。
          </p>
        </header>
  
        <!-- 专业技能 -->
        <section class="resume-section">
          <div class="resume-section-head">
            <span class="en-title">SKILLS</span>
            <h2>专业技能</h2>
          </div>
          <ul class="text-list">
            <li><strong>后端开发：</strong>熟练使用Java语言，掌握Spring Boot框架，具备系统接口开发、业务逻辑实现能力</li>
            <li><strong>前端开发：</strong>掌握Vue3、Element Plus，熟悉HTML/CSS/JavaScript，能实现响应式医疗类页面开发</li>
            <li><strong>数据库：</strong>熟练使用MySQL进行医疗数据存储、查询与优化，掌握系统数据库设计规范</li>
            <li><strong>开发工具：</strong>精通IntelliJ IDEA、VS Code、MySQL；熟悉Linux系统、Git版本控制、Maven依赖构建、Redis、DBeaver；Qoder AI等AI工具辅助开发，及若依脚手架</li>
            <li><strong>其他：</strong>了解中医诊疗基本流程与医疗信息化相关规范，具备需求分析、系统设计基础，编码规范严谨，问题排查能力强</li>
          </ul>
        </section>
  
        <!-- 工作经历 -->
        <section class="resume-section">
          <div class="resume-section-head">
            <span class="en-title">EXPERIENCE</span>
            <h2>工作经历</h2>
          </div>
          <div class="block">
            <div class="block-head">
              <span class="block-title">大连智捷企业管理发展集团有限公司</span>
              <span class="block-sub">Java实习工程师</span>
            </div>
            <p>学习若依脚手架并制作完善小区物业管理系统，完成两个较为完整的毕业设计demo：中医患者医护双端管理系统、助农器械租赁网站。</p>
          </div>
        </section>
  
        <!-- 开源项目及作品 -->
        <section class="resume-section">
          <div class="resume-section-head">
            <span class="en-title">PROJECTS</span>
            <h2>开源项目及作品</h2>
          </div>
  
          <!-- 项目1 -->
          <div class="block">
            <div class="block-head">
              <a
                class="project-title"
                href="https://www.bilibili.com/video/BV12xYF6cEkQ/?share_source=copy_web"
                target="_blank"
                rel="noopener noreferrer"
              >
                <strong>■ 中医患者医护双端管理系统（可点击查看视频）</strong>
              </a>
            </div>
            <p><strong>项目描述：</strong>搭建覆盖患者、医生、医院三方的中医诊疗一体化平台，整合预约挂号、健康管理、诊疗协作、中药及养生产品交易等功能，贴合中医诊疗习惯，实现“诊疗-购药-养生”全流程服务。</p>
            <p><strong>负责模块：</strong></p>
            <ul class="text-list">
              <li>参与需求分析与系统架构设计，搭建Spring Boot后端服务，设计MySQL数据库表结构（含患者档案、药方）</li>
              <li>开发医生端患者信息管理、电子药方生成/修改、跨诊室会诊等核心接口</li>
              <li>实现患者端预约挂号、健康档案查询、药品交易下单及支付对接功能</li>
              <li>配合前端使用Vue3+Element Plus完成页面交互开发，参与系统测试与优化</li>
            </ul>
            <p><strong>核心技术：</strong>Spring Boot、Vue3、Element Plus、MySQL、MyBatis、Maven、Git</p>
            <p><strong>项目成果：</strong>实现中医特色诊疗与合规交易一体化，支持中药配伍禁忌提示、三方数据实时同步，完成可运行的双端系统原型。</p>
          </div>
  
          <!-- 项目2 -->
          <div class="block">
            <div class="block-head">
              <a
                class="project-title"
                href="https://www.bilibili.com/video/BV12xYF6cEQv/?share_source=copy_web&vd_source=be0a82bd8149247ec708ac6c644f03ba"
                target="_blank"
              >
                <strong>■ 助农器械租赁网站（可点击查看视频）</strong>
              </a>
            </div>
            <p><strong>项目描述：</strong>将用户分为普通用户、器械商家、管理员三角色；实现器械审核、设备租赁、二手买卖、商家资质审核、订单、资金监管、结算提现、质检、评价、售后咨询整套业务。</p>
            <p><strong>负责模块：</strong></p>
            <ul class="text-list">
              <li>参与需求梳理，SpringBoot搭建后端，设计全套业务MySQL数据表；</li>
              <li>开发器械、租赁/二手订单、资质审核、资金流水、提现审批、评价售后全套CRUD接口；自动生成订单号；支持逻辑删除+管理员物理删除</li>
              <li>Vue3+ElementPlus开发用户、商家、管理员三端页面；表单校验、分页弹窗交互；完成前后端联调测试。</li>
            </ul>
            <p><strong>核心技术：</strong>Spring Boot、Vue3、Element Plus、MySQL、MyBatis、Maven、Git。</p>
            <p><strong>项目成果：</strong>完成可运行前后端分离原型，完整跑通器械租赁、二手交易、商家审核结算、售后反馈业务。</p>
          </div>
  
          <!-- 项目3 -->
          <div class="block">
            <div class="block-head">
              <span class="project-title"><strong>■ 小区物业管理系统（实习项目｜若依二次开发）</strong></span>
            </div>
            <p>采用前后端分离架构，基于若依（RuoYi-Vue）脚手架二次开发，复用框架自带用户、角色、菜单、字典权限体系，不修改底层源码；面向物业管理人员，实现楼宇-单元-楼层-房间四级房屋资源管理、住户信息与人屋对应、公共设施管理、报修工单流转、物业收费记录等日常物业业务。</p>
            <p><strong>核心技术：</strong>RuoYi-Vue、Spring Boot、Vue、MySQL</p>
          </div>
        </section>
  
        <!-- 教育背景 -->
        <section class="resume-section">
          <div class="resume-section-head">
            <span class="en-title">EDUCATION</span>
            <h2>教育背景</h2>
          </div>
          <ul class="text-list">
            <li><strong>学校：</strong>大连东软信息学院 | 本科</li>
            <li><strong>专业：</strong>软件工程</li>
            <li><strong>毕业时间：</strong>2026年6月</li>
            <li><strong>核心课程：</strong>Java编程、Spring Boot框架、Vue前端开发、数据库原理与应用、软件工程、Web开发技术等</li>
          </ul>
        </section>
  
      </div>
    </div>
  </template>
  
  <script setup>
  </script>
  
  <style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  body {
    font-family: "Microsoft YaHei", "PingFang SC", "宋体", system-ui, sans-serif;
    background-color: #e5e7eb;
    color: #222;
    line-height: 1.6;
  }
  
  .resume-page {
    padding: 40px 20px;
  }
  
  .resume-container {
    max-width: 900px;
    margin: 0 auto;
    background: #ffffff;
    padding: 40px 48px;
    box-shadow: 0 2px 12px rgba(0, 0, 0, 0.08);
  }
  
  /* 头部 */
  .resume-header {
    margin-bottom: 28px;
    text-align: left;
  }
  
  .resume-name {
    font-size: 34px;
    font-weight: 700;
    color: #111827;
    margin-bottom: 8px;
    text-align: center;
  }
  
  .resume-contact,
  .resume-meta {
    display: flex;
    flex-wrap: wrap;
    gap: 18px;
    font-size: 14px;
    color: #333;
    margin-bottom: 6px;
    justify-content: center;
  }
  
  .resume-job {
    font-weight: 600;
    color: #2563eb;
  }
  
  .resume-summary {
    font-size: 14px;
    color: #333;
    margin-top: 10px;
    text-align: left;
  }
  
  /* 模块标题 */
  .resume-section {
    margin-bottom: 26px;
  }
  
  .resume-section-head {
    display: flex;
    align-items: baseline;
    gap: 14px;
    border-bottom: 2px solid #111827;
    padding-bottom: 6px;
    margin-bottom: 14px;
    text-align: left;
  }
  
  .en-title {
    font-size: 13px;
    font-weight: 700;
    color: #6b7280;
    letter-spacing: 1px;
    text-transform: uppercase;
  }
  
  .resume-section-head h2 {
    font-size: 18px;
    font-weight: 700;
    color: #111827;
  }
  
  /* 正文块 */
  .block {
    margin-bottom: 20px;
    text-align: left;
  }
  
  .block:last-child {
    margin-bottom: 0;
  }
  
  .block-head {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    gap: 12px;
    margin-bottom: 8px;
    text-align: left;
  }
  
  .block-title {
    font-weight: 700;
    font-size: 15px;
    color: #111827;
  }
  
  .block-sub {
    font-size: 14px;
    color: #555;
  }
  
  /* 列表 */
  .text-list {
    list-style: none;
    padding-left: 0;
    margin-top: 6px;
    margin-bottom: 10px;
    text-align: left;
  }
  
  .text-list li {
    position: relative;
    padding-left: 18px;
    margin-bottom: 4px;
    font-size: 14px;
    color: #333;
  }
  
  .text-list li::before {
    content: "•";
    position: absolute;
    left: 0;
    top: 0;
    color: #2563eb;
    font-weight: 700;
  }
  
  /* 项目标题 */
  .project-title {
    font-size: 15px;
    font-weight: 700;
    color: #111827;
    text-decoration: underline;
    transition: color 0.2s;
  }
  
  .project-title:hover {
    color: #2563eb;
  }
  
  /* 段落 */
  .block p {
    font-size: 14px;
    color: #333;
    margin-bottom: 6px;
    text-align: left;
  }
  
  strong {
    color: #111827;
  }
  
  /* 移动端 */
  @media (max-width: 768px) {
    .resume-page {
      padding: 12px;
    }
  
    .resume-container {
      padding: 28px 22px;
    }
  
    .resume-name {
      font-size: 28px;
    }
  
    .block-head {
      flex-direction: column;
      align-items: flex-start;
      gap: 2px;
    }
  }
  </style>
  