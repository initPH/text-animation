<!-- MyBook.vue -->
<template>
  <div class="container">
    <pre id="codeEdit"></pre>
    <div class="wrapper" style="display: none">
      <header class="header">
        <h1>彭&nbsp;&nbsp;&nbsp;&nbsp;浩</h1>
        <h2 class="apply-position">web前端开发</h2>
      </header>
      <div class="main-container">
        <aside class="content-aside">
          <section>
            <h2 class="block-title">基本信息</h2>
            <div class="base-info-items">
              <div class="base-info-item">年龄：25</div>
              <div class="base-info-item">学历：本科</div>
              <div class="base-info-item">英语：CET-4</div>
              <div class="base-info-item">毕业时间：2018.6</div>
              <div class="base-info-item">毕业院校：重庆邮电大学</div>
            </div>
          </section>
          <hr />
          <section>
            <h2 class="block-title">相关技能</h2>
            <h3 class="block-sub-title">前端基础</h3>
            <div id="frontBase"></div>
            <br />
            <h3 class="block-sub-title">前端JS框架</h3>
            <div id="jsFramework"></div>
            <br />
            <h3 class="block-sub-title">前端UI框架</h3>
            <div id="uiFramework"></div>
            <br />
            <h3 class="block-sub-title">前端JS工具</h3>
            <div id="jsTool"></div>
            <br />
            <h3 class="block-sub-title">其他</h3>
            <div id="otherInfo"></div>
          </section>
          <hr />
          <section>
            <h2 class="block-title">联系方式</h2>
            <div class="contact-ways">
              <div class="contact-way">
                <svg
                  t="1618318768017"
                  class="icon"
                  viewBox="0 0 1024 1024"
                  version="1.1"
                  xmlns="http://www.w3.org/2000/svg"
                  p-id="1149"
                  width="24"
                  height="24"
                >
                  <path
                    d="M725.681633 902.791837c-38.661224 0-82.02449-7.314286-127.477551-21.420408-109.191837-33.959184-216.816327-105.012245-303.020409-200.09796C166.138776 538.644898 104.489796 396.538776 116.506122 270.106122c3.657143-31.346939 13.583673-71.053061 60.604082-102.922449 36.04898-29.257143 77.322449-45.97551 109.714286-45.453061 33.959184 0.522449 45.453061 12.538776 80.457143 63.216327 53.812245 74.187755 57.469388 110.759184 55.379591 131.657143-3.657143 34.481633-22.465306 49.632653-39.706122 63.216326-4.179592 3.134694-8.359184 6.791837-12.016326 9.926531-20.897959 26.644898-46.497959 63.738776 63.216326 177.110204 93.518367 89.861224 144.195918 100.832653 165.616327 99.265306 16.718367-1.044898 22.987755-9.926531 25.6-13.061225l0.522449-0.522448c35.004082-49.110204 46.497959-61.126531 79.934693-66.351021 32.391837-5.22449 49.110204 5.22449 118.07347 48.587755 62.171429 39.183673 90.906122 65.306122 84.636735 106.579592-2.089796 44.930612-36.571429 106.057143-75.232654 133.746939-26.644898 18.285714-63.738776 27.689796-107.624489 27.689796z"
                    fill="#16C4AF"
                    p-id="1150"
                  ></path>
                </svg>
                <div class="phone">15802381801</div>
              </div>
              <div class="contact-way">
                <svg
                  t="1618318961314"
                  class="icon"
                  viewBox="0 0 1024 1024"
                  version="1.1"
                  xmlns="http://www.w3.org/2000/svg"
                  p-id="2027"
                  width="24"
                  height="24"
                >
                  <path
                    d="M683.058 364.695c11 0 22 1.016 32.943 1.976C686.564 230.064 538.896 128 370.681 128c-188.104 0.66-342.237 127.793-342.237 289.226 0 93.068 51.379 169.827 136.725 229.256L130.72 748.43l119.796-59.368c42.918 8.395 77.37 16.79 119.742 16.79 11 0 21.46-0.48 31.914-1.442a259.168 259.168 0 0 1-10.455-71.358c0.485-148.002 128.744-268.297 291.403-268.297l-0.06-0.06z m-184.113-91.992c25.99 0 42.913 16.79 42.913 42.575 0 25.188-16.923 42.579-42.913 42.579-25.45 0-51.38-16.85-51.38-42.58 0-25.784 25.93-42.574 51.38-42.574z m-239.544 85.154c-25.384 0-51.374-16.85-51.374-42.58 0-25.784 25.99-42.574 51.374-42.574 25.45 0 42.918 16.79 42.918 42.575 0 25.188-16.924 42.579-42.918 42.579z m736.155 271.655c0-135.647-136.725-246.527-290.983-246.527-162.655 0-290.918 110.88-290.918 246.527 0 136.128 128.263 246.587 290.918 246.587 33.972 0 68.423-8.395 102.818-16.85l93.809 50.973-25.93-84.677c68.907-51.93 120.286-119.815 120.286-196.033z m-385.275-42.58c-16.923 0-34.452-16.79-34.452-34.179 0-16.79 17.529-34.18 34.452-34.18 25.99 0 42.918 16.85 42.918 34.18 0 17.39-16.928 34.18-42.918 34.18z m188.165 0c-16.984 0-33.972-16.79-33.972-34.179 0-16.79 16.927-34.18 33.972-34.18 25.93 0 42.913 16.85 42.913 34.18 0 17.39-16.983 34.18-42.913 34.18z"
                    fill="#09BB07"
                    p-id="2028"
                  ></path>
                </svg>
                <div class="wechat">ph11567</div>
              </div>
              <div class="contact-way">
                <svg
                  t="1618319003673"
                  class="icon"
                  viewBox="0 0 1024 1024"
                  version="1.1"
                  xmlns="http://www.w3.org/2000/svg"
                  p-id="2862"
                  width="24"
                  height="24"
                >
                  <path
                    d="M751.1 685.9H294.2c-23.7 0-43.2-19.4-43.2-43.2V364.1c0-23.7 19.4-43.2 43.2-43.2h456.9c23.7 0 43.2 19.4 43.2 43.2v278.6c0 23.8-19.4 43.2-43.2 43.2z"
                    fill="#FEE632"
                    p-id="2863"
                  ></path>
                  <path
                    d="M124.37 756.852l279.65-253.71 27.952 30.81-279.65 253.709zM618.435 532.05l28.712-30.101 252.971 241.294-28.712 30.101z"
                    fill="#231815"
                    p-id="2864"
                  ></path>
                  <path
                    d="M526.8 636.9h-1.5c-17.8-0.4-34.6-7.6-47.4-20.4l-0.4-0.4-347.1-367 30.2-28.6 346.9 366.8c5.1 5 11.8 7.9 18.7 8 6.5 0.1 12.5-2.1 17-6.5l327-365.7 31 27.7-327.8 366.7-0.4 0.5c-12.3 12.2-28.6 18.9-46.2 18.9z"
                    fill="#231815"
                    p-id="2865"
                  ></path>
                  <path
                    d="M841.4 823.7H173.1c-48 0-87-39-87-87V286.9c0-48 39-87 87-87h668.3c48 0 87 39 87 87v449.9c0 47.9-39 86.9-87 86.9zM173.1 241.5c-25 0-45.4 20.4-45.4 45.4v449.9c0 25 20.4 45.4 45.4 45.4h668.3c25 0 45.4-20.4 45.4-45.4V286.9c0-25-20.4-45.4-45.4-45.4H173.1z"
                    fill="#231815"
                    p-id="2866"
                  ></path>
                </svg>
                <div class="email">949898050@qq.com</div>
              </div>
              <!-- <div class="contact-way">
              <svg t="1618328318031" class="icon" viewBox="0 0 1024 1024" version="1.1"
                xmlns="http://www.w3.org/2000/svg" p-id="2009" width="24" height="24">
                <path
                  d="M110.933333 451.84L357.546667 204.8l72.106666 72.533333c-10.24 36.266667 6.4 75.946667 39.68 95.146667v236.373333c-25.6 14.506667-42.666667 42.24-42.666666 73.813334a85.333333 85.333333 0 0 0 85.333333 85.333333 85.333333 85.333333 0 0 0 85.333333-85.333333c0-31.573333-17.066667-59.306667-42.666666-73.813334V401.493333l88.32 89.173334c-2.986667 6.4-2.986667 13.653333-2.986667 21.333333a85.333333 85.333333 0 0 0 85.333333 85.333333 85.333333 85.333333 0 0 0 85.333334-85.333333 85.333333 85.333333 0 0 0-85.333334-85.333333c-7.68 0-14.933333 0-21.333333 2.986666L594.346667 320a84.48 84.48 0 0 0-49.066667-99.84c-18.346667-6.826667-37.546667-8.533333-54.613333-3.84L418.133333 144.213333l33.706667-33.28c33.28-33.706667 87.04-33.706667 120.32 0l340.906667 340.906667c33.706667 33.28 33.706667 87.04 0 120.32l-340.906667 340.906667c-33.28 33.706667-87.04 33.706667-120.32 0L110.933333 572.16c-33.706667-33.28-33.706667-87.04 0-120.32z"
                  fill="#E64A19" p-id="2010"></path>
              </svg>
              <div class="git"></div>
            </div> -->
              <div class="contact-way">
                <svg
                  t="1618319088031"
                  class="icon"
                  viewBox="0 0 1024 1024"
                  version="1.1"
                  xmlns="http://www.w3.org/2000/svg"
                  p-id="4485"
                  width="24"
                  height="24"
                >
                  <path
                    d="M833.536 667.136h-256l74.24-106.496c2.048-3.072 5.12-5.632 8.704-7.68 74.752-40.448 121.344-118.272 121.344-203.776 0-127.488-102.912-230.912-229.376-230.912S322.56 222.208 322.56 349.696c0 84.992 46.592 163.328 121.344 203.776 3.584 2.048 6.656 4.608 8.704 7.68l74.24 106.496H315.392l-178.688 250.368h857.6l-160.768-250.88z"
                    fill="#17E6A1"
                    p-id="4486"
                  ></path>
                  <path
                    d="M377.344 593.408l113.664 161.792c7.68 11.264 23.04 13.824 33.792 6.144 2.048-1.536 4.096-3.584 6.144-6.144l113.664-161.792c86.016-48.128 138.752-138.752 138.752-237.568 0-150.016-122.368-272.384-272.384-272.384S238.592 205.312 238.592 355.84c0 98.816 52.736 188.928 138.752 237.568z m133.632-461.312c123.392 0 223.744 100.352 223.744 223.744 0 82.432-45.056 158.208-118.272 197.12-3.584 2.048-6.144 4.608-8.192 7.68l-97.28 137.728-97.28-137.728c-2.048-3.072-5.12-5.632-8.192-7.68-72.704-38.912-118.272-114.688-118.272-197.12 0-123.392 100.352-223.744 223.744-223.744z m0 345.6c68.096 0 123.392-55.296 123.392-123.392s-55.296-123.392-123.392-123.392S387.584 286.72 387.584 354.816c0 67.584 55.296 122.88 123.392 122.88z m0-197.632c40.96 0 74.24 33.28 74.24 74.24s-33.28 74.24-74.24 74.24-74.24-33.28-74.24-74.24c0-40.448 33.28-74.24 74.24-74.24z m471.552 649.216c-4.096 7.68-12.288 11.264-21.504 11.264H60.416c-8.704 0-16.896-3.584-21.504-11.264-4.096-7.68-4.096-16.384 0.512-24.064l147.456-242.176c4.608-7.168 12.288-12.8 20.992-12.8H358.4c13.312 0 24.576 11.264 24.576 24.576s-10.752 24.576-24.576 24.576H221.696l-117.76 191.488h813.568l-117.248-191.488h-136.704c-13.312 0-24.576-11.264-24.576-24.576s10.752-24.576 24.576-24.576H814.08c8.704 0 16.384 6.144 20.992 13.312l147.456 241.152c4.096 7.168 4.608 16.896 0 24.576z"
                    fill="#272636"
                    p-id="4487"
                  ></path>
                </svg>
                <div class="address">成都-武侯区</div>
              </div>
            </div>
          </section>
        </aside>
        <main class="main-content">
          <div class="job-exp">
            <h2 class="block-title">工作经历</h2>
            <div class="flex-between">
              <h4>重庆云崛浩数有限公司</h4>
              <h4>前端开发</h4>
              <h4>2019.02 - 2021.03</h4>
            </div>
            <div class="job-detail">
              <div>
                1、<span class="highlight">前端组长</span>，负责公司网页、小程序的<span class="highlight"
                  >开发、部署</span
                >与<span class="highlight">维护</span>
              </div>
              <div>2、开发设计可重用的业务<span class="highlight">组件</span></div>
              <div>3、负责公司<span class="highlight">新人的指导</span>,帮助新人了解项目和开发过程</div>
              <div>4、负责公司项目前端的<span class="highlight">进度管理</span>,使项目如期进行</div>
              <div>5、<span class="highlight">改造</span>老项目,项目由node部署改为nginx部署</div>
              <div>6、前端技术分享, 提升团队技术水平</div>
            </div>
            <div class="flex-between">
              <h4>广东信通通信有限公司</h4>
              <h4>前端开发</h4>
              <h4>2018.03 - 2019.01</h4>
            </div>
            <div class="job-detail">
              <div>
                1、参与公司生产指挥平台项目的<span class="highlight">开发</span>,地图与周围模块的<span class="highlight"
                  >交互</span
                >
              </div>
              <div>2、与客户沟通获取展示数据,与后端交流<span class="highlight">请求数据</span>进行展示</div>
              <div>3、与产品经理和视觉设计工程师,<span class="highlight">紧密沟通</span> ,改善页面UI和交互方式</div>
              <div>4、负责公司项目配套的硬件的安装</div>
            </div>
            <hr />
          </div>
          <div class="project-exp">
            <h2 class="block-title">项目经历</h2>
            <div class="project-detail">
              <h3>国资监管系统(国资委端、企业端)</h3>
              <h4 class="tech-stack">技术栈：vue全家桶 / ElementUI / jsencript / nodejs / request / express</h4>
              <div>
                <b>项目介绍</b
                >：基于vue开发的子企业与主企业之间日常工作的管理系统。主企业下发任务,子企业填报任务,提交数据。通知通报、政策法规的下发与查看。
              </div>
              <div><b>项目职责</b></div>
              <div class="project-dutys">
                <p class="intent">
                  参与系统两个端项目的搭建,<span class="highlight">请求的封装</span>,与后端讨论,更好的<span
                    class="highlight"
                    >实现需求</span
                  >
                </p>
                <p class="intent">
                  <span class="highlight">登录模块、角色权限模块</span>的开发,以及登录之后获取菜单,<span
                    class="highlight"
                    >递归</span
                  >渲染菜单组件开发。
                </p>
                <p class="intent">
                  <span class="highlight">独立完成</span> 基于 Element UI 组件 实现的 列表页、详情页、编辑页
                  等常用页面的 <span class="highlight">模板封装</span>
                </p>
                <p class="intent">
                  负责项目后续bug的修改,需求的变更与<span class="highlight">需求确认</span>,负责项目的<span
                    class="highlight"
                    >远程部署</span
                  >和本地测试环境的部署,以及项目的<span class="highlight">进度监管</span>
                </p>
              </div>
              <div>
                <b>技术要点</b>：项目使用 <span class="highlight">Vue CLI2</span> 搭建项目环境; 使用
                <span class="highlight">Vuex</span> 做状态管理; 使用
                <span class="highlight">Element UI</span> 作页面布局及 交互 ; 使用 Less 作 CSS 预处理 ; 通过
                <span class="highlight">Vue Router</span>实现路由的跳转、<span class="highlight">axios</span
                >进行请求、权限验证等;使用<span class="highlight">jsencript</span>登录加密,使用<span class="highlight"
                  >nodejs,express,request</span
                >进行请求的转发和部署
              </div>
            </div>
            <div class="project-detail">
              <h3>国资委大数据展示平台</h3>
              <h4 class="tech-stack">技术栈：vue全家桶 /flex布局 / echarts / wordCloud / nodejs / request / express</h4>
              <div>
                <b>项目介绍</b
                >：基于vue、echarts、flex布局开发的数据展示平台,对国资委企业端上传提交的数据进行统计展示、通过wordcloud词云分析舆情的情况,对接第三方接口,获取企业的工商信息进行展示
              </div>
              <div><b>项目职责</b></div>
              <div class="project-dutys">
                <p class="intent"><span class="highlight">独立完成</span>项目的搭建和初始化</p>
                <p class="intent">各种图表如柱状图、折线图、饼图的<span class="highlight">组件封装</span></p>
                <p class="intent">使用<span class="highlight">关系图</span>,展示企业之间对应的关系</p>
                <p class="intent">
                  负责项目后续bug的修改,需求的变更与<span class="highlight">需求确认</span>,负责项目的<span
                    class="highlight"
                    >远程部署</span
                  >和本地测试环境的部署,以及项目的<span class="highlight">进度监管</span>
                </p>
              </div>
              <div>
                <b>技术要点</b>：使用<span class="highlight">vue-cli3</span>进行项目的构建,使用<span class="highlight"
                  >flex</span
                >布局,<span class="highlight">echarts</span>实现柱状图、折线图、雷达图、关系图、地图、树状图等等,
                页面使用<span class="highlight">rem</span>为单位,当窗口大小改变时,结合<span class="highlight">防抖</span
                >函数,实时设置rem的大小,做到实时适应窗口
              </div>
            </div>
            <div class="project-detail">
              <h3>鲜芸巷微信小程序</h3>
              <h4 class="tech-stack">技术栈：uniapp / flex布局 / uview / uni.request / 微信小程序</h4>
              <div>
                <b>项目介绍</b
                >：基于uniapp开发的在线的社区团购小程序,包含商品浏览、选购、提货扫描、购物车、订单、定位、优惠券、直播、在线支付等功能
              </div>
              <div><b>项目职责</b></div>
              <div class="project-dutys">
                <p class="intent">负责小程序的上线,更新</p>
                <p class="intent">
                  负责小程序<span class="highlight">首页</span>,商品浏览页面的开发,商品item组件的开发
                </p>
                <p class="intent">
                  负责优惠券<span class="highlight">组件</span>的开发,使用微信自带的<span class="highlight">直播</span
                  >插件直播
                </p>
                <p class="intent">
                  负责<span class="highlight">购物车</span>的开发,订单页面的价格<span class="highlight">自动计算</span
                  >、<span class="highlight">微信支付</span>
                </p>
              </div>
              <div>
                <b>技术要点</b>：使用<span class="highlight">hbuilderX</span
                >创建的uniapp项目,用到vuex管理当前角色,使用<span class="highlight">uview</span>UI框架布局和交互,对<span
                  class="highlight"
                  >uni.request</span
                >
                进行请求封装,<span class="highlight">uni.chooseImage</span>选择图片或拍照,<span class="highlight"
                  >uni.getLocation</span
                >获取定位,使用<span class="highlight">live-player-plugin</span>插件进行直播等功能
              </div>
            </div>
          </div>
          <hr />
          <div class="opensource-project">
            <h2 class="block-title">开源项目</h2>
            <div class="project-detail">
              <h3>ph小说阅读器</h3>
              <h4 class="tech-stack">技术栈：uniapp / flex布局 / uni.request / 网页分析</h4>
              <div>
                <b>项目介绍</b
                >：利用爬虫的思想，使用uniapp开发的纯前端的安卓小说阅读器，无广告，有阅读记录、搜索、搜索记录、换源、目录、主题切换、字体大小设置等功能。
              </div>
              <div><b>项目职责</b></div>
              <div class="project-dutys">
                <p class="intent">独立设计与开发</p>
                <p class="intent">使用uniapp自带的<span class="highlight">uni.request</span>请求在线网站的数据</p>
                <p class="intent">使用<span class="highlight">cheerio</span>匹配到小说内容，剔除广告</p>
                <p class="intent">
                  <span class="highlight">纯前端，无服务器</span>。历史阅读、历史搜索等数据都存在本地。
                </p>
              </div>
              <div>
                <b>技术要点</b>：使用uniapp开发的安卓软件，<span class="highlight">安卓打包</span>,
                <span class="highlight">换源</span>搜索，并且根据不同的源储存<span class="highlight">阅读记录</span
                >以便<span class="highlight">继续阅读</span>，<span class="highlight">分析目标网站</span
                >的数据请求，<span class="highlight">爬取</span>网页的数据。 下拉刷新、<span class="highlight"
                  >scroll-view</span
                >的刷新等
              </div>
              <div><b>github地址</b>：https://github.com/initPH/novelReader</div>
            </div>
          </div>
        </main>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { ref, reactive } from 'vue';
import prismjs from 'prismjs';
// import 'prismjs/themes/prism.css';
export default {
  props: {
    collectionName: String,
  },
  mounted() {
    function insertTagParagraph(domId: string) {
      let dom = document.getElementById(domId);
      return function tagParagraph(stringArr: any, ...tags: any) {
        let result = '';
        for (let index = 0; index < stringArr.length; index++) {
          if (index < stringArr.length - 1) {
            result += `${stringArr[index]}<span class="highlight">${tags[index]}</span>`;
          } else {
            result += stringArr[index];
          }
        }
        let p = document.createElement('p');
        // p.classList = ['intent']
        p.className = 'intent';
        p.innerHTML = result;
        if (dom) dom.appendChild(p);
      };
    }
    // 前端基础
    const frontBase = insertTagParagraph('frontBase');
    frontBase`熟练使用${'div+css'}页面布局, ${'flex'}布局,
    了解${'css盒子模型'},根据设计图${'高度还原'}`;
    frontBase`有扎实的原生javascript基础,熟练使用es6以上常用规范,掌握重要概念如:
    ${'原型'}、${`闭包`}、${'作用域链'}、${'Promise'}、${'async await'}、${'js循环机制'}等`;
    frontBase`了解${'http'}协议,浏览器常用储存的几种方式`;

    // js框架
    const jsFramework = insertTagParagraph('jsFramework');
    jsFramework`三年${'vue'}框架的使用经验,
    熟悉vue的${'vue全家桶'}的使用,了解${'mvvm'}原理、熟悉vue${'生命周期'}、${'组件间通信'}
    、了解${'webpack'}的配置,能够${'独立'}从零进行开发。`;
    jsFramework`一年${'uniapp'}框架的使用,熟悉uniapp自带的api,
    如${'uni.request'}、${'uni.navigateTo'}以及${'页面生命周期'}、熟悉微信小程序的发布流程`;

    // UI框架
    const uiFramework = insertTagParagraph('uiFramework');
    uiFramework`熟练使用${'ElementUI'}的各个组件,修改ElementUI的${'主题'},并且能根据需求二次封装,
    了解${'vant、iview'}等ui框架。了解uni-app生态的框架${'uview'}`;

    // UI框架
    const jsTool = insertTagParagraph('jsTool');
    jsTool`熟练使用${'echarts'}进行各种图表的绘制,了解${'antv'}。`;

    // 其他信息
    const otherInfo = insertTagParagraph('otherInfo');
    otherInfo`熟练使用${'nginx'}部署项目,了解${'nodeJs'},有用过${'express'}框架对请求进行转发,了解${'pm2'},使用pm2对nodejs项目进行部署`;
    otherInfo`了解${'electron'},曾用electron开发过一个pc端人脸识别就餐的软件`;
    otherInfo`了解${'python'},偶尔在项目中利用${'python'}对excel的数据进行操作,
    获得页面展示需要的数据,早期也用python的${'flask'}框架写过页面和${'接口'}`;
  },
  setup() {
    const readersNumber = ref(0);
    const book = reactive({ title: 'Vue 3 Guide' });

    let styleStr = `
    /*
    * 面试官你好，我是Ph,重庆潼南人
    * 为您精心准备一份不一样的简历来介绍自己
    * 首先准备一些样式
    */
   /* 先给所有效果加个过度 */
    *{
        transition: all .8s;
        margin: 0;
        padding: 0;
    }
    
    /* 稍等，在容器上添加点样式 */
    .container {
      background: #fff;
    }
    #codeEdit{
        color: #fff;
        background: #1E1E1E;
        height: 100vh;
        overflow: scroll;
        width: 500px;
        padding-left: 10px;
        position: fixed;
        left: 0
    }
    #resume{
        box-shadow: -1px 4px 9px 3px rgba(0, 0, 0, .15);
    }
    /* 我需要一点代码高亮 */
    pre#codeEdit{
        color: #CE9e78;
    }
    .token.selector{
        color: rgb(230, 155, 43);
    }
    .token.comment{
        color: #6A9955;
        font-size: 14px;
    }
    .token.property{
        color: #60C8FE;
    }
    .token.function {
        color: #DD4A68;
    }
    /* 接下来请欣赏我的个人简历吧 */
    .wrapper {
      padding-left: 520px;
      display: block !important;
    }
    hr {
      color: #ccc;
      margin: 20px 0;
    }
    .intent {
      text-indent: 2em;
      line-height: 1.5;
      word-break: break-all;
      text-align: justify;
    }

    /* 每一块title的颜色 */
    .block-title {
      color: #2397DF;
      padding-bottom: 20px;
    }
    /* 二级title */
    .block-sub-title {
      padding-bottom: 10px;
    }

    /* 高亮 */
    .highlight {
      color: #FF5700;
      border-radius: 5px;
      background: #efefef;
    }

    .flex-between {
      display: flex;
      justify-content: space-between;
    }




    body {
      /* color: #333; */
      color: rgb(102,102,102);
      font-family: "Palatino Linotype", "Book Antiqua", Palatino;
      background: rgb(195, 188, 178);
    }

    .wrapper {
      width: 960px;
      margin: 0 auto;
      background: #fff;
      overflow: hidden;
      min-height: 100vh;
    }

    .header {
      background: rgb(64, 64, 65);
      width: 100%;
      text-align: center;
      padding: 30px 0;
      position: relative;
      color: #fff;
    }

    .apply-position {
      color: #999;
      padding-top: 10px;
    }

    /* 整体左右留个位置 */
    .main-container {
      padding: 20px 0;
      display: flex;
      border: 1px solid #aaa;
    }

    .content-aside {
      width: 300px;
      flex-shrink: 0;
      padding: 0 20px;
      box-sizing: border-box;
      border-right: 2px solid #ccc;
      padding-bottom: 9999px;
      margin-bottom: -9999px;
    }

    .base-info-items {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
    }

    .base-info-items .base-info-item {
      flex-basis: 50%;
      line-height: 1.5;
    }
    .base-info-item:last-child {
      flex-basis: 100%;
    }

    .contact-ways {
      margin-top: 15px;
    }

    .contact-way {
      display: flex;
      line-height: 1.8;
    }

    .phone,.wechat,.email,.address {
      margin-left: 10px;
    }


    /* 主要中间的内容 */
    .main-content {
      padding: 0 30px;
      flex-grow: 1;
    }

    .job-detail {
      margin: 20px 0;
      line-height: 1.8;
    }

    .project-detail {
      line-height: 1.8;
      margin-bottom: 20px;
      text-align: justify;
    }


    .project-dutys {
      margin: 5px 0;
    }
    .project-dutys p{
      line-height: 1.8;
    }

    @media print {
      body {
        background: transparent;
      }
    }
`;
    let num = 0;
    let styleTag = document.createElement('style');
    document.head.appendChild(styleTag);
    let interval = setInterval(() => {
      if (num < styleStr.length) {
        (document.querySelector('#codeEdit') as HTMLElement).innerHTML = prismjs.highlight(
          styleStr.slice(0, num),
          prismjs.languages.css,
        ) as string;
        num++;
        (document.querySelector('#codeEdit') as HTMLElement).scrollTop = 99999;
        styleTag.innerHTML = styleStr.slice(0, num);
      } else {
        clearInterval(interval);
      }
    }, 10);

    let style = document.createElement('style');
    // document.head.appendChild(style)

    // 暴露给 template
    return {
      readersNumber,
      book,
    };
  },
};
</script>
