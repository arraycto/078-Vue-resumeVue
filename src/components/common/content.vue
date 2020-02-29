<template>
  <div class="content-bd">
    <div class="content-left">
      <section class="practice">
        <header class="section-hd">
          <span class="section-title-l"></span>
          <h2 class="section-title">项目经历</h2>
          <span class="section-title-r"></span>
        </header>
        <div class="section-bd">

          <!--经历:绿豆芽科技-->
          <div class="item">
            <header class="item-hd">
              <h3 class="item-name">西安绿豆芽信息科技有限公司(西安)</h3>
              <span class="item-time">2018.01 至 2020.02</span>
              <a class="btn item-more"
                 href="https://baike.baidu.com/item/%E8%A5%BF%E5%AE%89%E7%BB%BF%E8%B1%86%E8%8A%BD%E4%BF%A1%E6%81%AF%E7%A7%91%E6%8A%80%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8"
                 target="_blank" title="点击查看->西安绿豆芽信息科技有限公司百度百科">工作</a>
            </header>
            <ol class="item-project">
              <li class="project-1">
                <h3 class="project-name">
                  <a href="http://www.bitchang.com" target="_blank"
                     title="点击进入->币厂交易所首页">数字货币交易所</a></h3>
                <ol>
                  <li class="project-2">
                    <div class="item-bd">
                      <h3 class="project-name-2">交易所后端</h3>
                      <div class="div-item">
                        <h3 class="project-des">【项目简介】</h3>
                        <p class="item-project-des">
                          该项目为数字货币交易所，为用户提供便捷的数字资产交易系统，包括币币交易、法币交易、行情查看等主要功能。后端开发语言采用Java，主要采用Spring boot + Hibernate
                          JPA作为后端基础服务框架；项目后端服务主要包含：API网关、JWT用户认证、去中心化钱包的资金管理、交易系统、交易订单撮合引擎、WebSocket
                          K线数据分发服务以及钱包系统（区块链链上操作）等多项服务组成。</p>
                      </div>
                      <div class="div-item">
                        <h3 class="project-des">【工作职责】</h3>
                        <ul class="section-content">
                          <li>负责项目框架搭建以及疑难问题解决，为项目成员提供开发思路</li>
                          <li>主导整个项目正常开发流程，研究了高可用、高并发服务器的架构设计（keepalived+nginx+haproxy）</li>
                          <li>对常用数据进行缓存处理（Redis），并对[撮合引擎]系统进行了架构设计，采用Redis内存撮合、Rabbit MQ消息队列异步入库实现高性能撮合系统，从而实现撮合引擎弹性伸缩
                          </li>
                          <li>
                            针对Redis可能出现脏读的问题可以采用消息队列处理，消除多线程同一时间操作同一Redis数据的脏读问题；或可以通过Redis锁解决高并发的脏读问题（不推荐，可能会造成无效等待）
                          </li>
                        </ul>
                      </div>
                    </div>
                  </li>
                  <li class="project-2">
                    <div class="item-bd">
                      <h3 class="project-name-2">交易所前端</h3>
                      <div class="div-item">
                        <h3 class="project-des">【项目简介】</h3>
                        <p class="item-project-des">该项目前端开发框架采用目前市面流行的Vue.js框架与Element UI
                          2.0。K线、行情等数据全通过websocket进行数据传输，解决了大量数据通过http请求造成服务端压力过大的问题，也保证了数据的时效性；K线图表采用国外TradingView工具，高效且专业的解决企业在数据图表绘制的问题；在应用数据存储上采用vuex实现多页面数据共享。</p>
                      </div>
                      <div class="div-item">
                        <h3 class="project-des">【工作职责】</h3>
                        <ul class="section-content">
                          <li>负责项目框架搭建以及疑难问题解决，为项目成员提供开发思路</li>
                          <li>主导整个项目正常开发流程，研究K线渲染组件TradingView的使用与原理</li>
                        </ul>
                      </div>
                    </div>
                  </li>
                  <li class="project-2">
                    <div class="item-bd">
                      <h3 class="project-name-2">以太坊智能合约开发</h3>
                      <div class="div-item">
                        <h3 class="project-des">【项目简介】</h3>
                        <p class="item-project-des">
                          以太坊的智能合约并非现实中常见的合同，而是存在区块链上，可以被触发执行的一段程序代码，这些代码实现了某种预定的规则，是存在于以太坊执行环境中的“自治代理”。智能合约是在以太坊虚拟机上运行的应用程序。</p>
                      </div>
                      <div class="div-item">
                        <h3 class="project-des">【工作职责】</h3>
                        <ul class="section-content">
                          <li>在法律允许或不触犯法律的条件下，负责公司在数字货币、智能合约开发上的需求</li>
                        </ul>
                      </div>
                    </div>
                  </li>
                  <li class="project-2">
                    <div class="item-bd">
                      <h3 class="project-name-2">交易所APP开发</h3>
                      <div class="div-item">
                        <h3 class="project-des">【项目简介】</h3>
                        <p class="item-project-des">该项目移动APP端采用Java进行原生Android
                          APP开发，项目主要涉及网络请求、底层框架设计、WebSocket、KLine图表绘制、实时交易处理展示等功能。</p>
                      </div>
                      <div class="div-item">
                        <h3 class="project-des">【工作职责】</h3>
                        <ul class="section-content">
                          <li>负责Android端APP基础框架搭建，采用xUtils进行网络请求</li>
                          <li>websocket进行实时数据传输，与服务端建立长链接</li>
                          <li>K线图表采用MPAndroidChart库做二次开发。</li>
                        </ul>
                      </div>
                    </div>
                  </li>
                </ol>
              </li>
              <li class="project-1">
                <h3 class="project-name">
                  <a href="http://www.bitchang.com" target="_blank"
                     title="点击进入->数字货币钱包">数字货币钱包</a>
                </h3>
                <ol>
                  <li class="project-2">
                    <div class="item-bd">
                      <h3 class="project-name-2">钱包APP</h3>
                      <div class="div-item">
                        <h3 class="project-des">【项目简介】</h3>
                        <p class="item-project-des">
                          该项目是一款加密数字货币钱包项目，为用户提供区块链数字货币钱包功能，包含：转账、收付款、资产查看、合约挖矿、共振等功能。主要涉及区块链链上交易发起及获取链上数据、合约挖矿订单等操作，可通过对应公链提供的API进行功能开发或通过JSON
                          RPC进行开发。</p>
                      </div>
                      <div class="div-item">
                        <h3 class="project-des">【工作职责】</h3>
                        <ul class="section-content">
                          <li>负责项目框架搭建以及链上交互开发</li>
                          <li>通过公链提供API以及JSON RPC文档实现数字货币转账、充提币、钱包创建等逻辑</li>
                        </ul>
                      </div>
                    </div>
                  </li>
                </ol>
              </li>
              <li class="project-1">
                <h3 class="project-name">
                  <a href="http://www.ledianyun.com/" target="_blank"
                     title="点击进入->乐店云商城系统">乐店云商城系统</a>
                </h3>
                <ol>
                  <li class="project-2">
                    <div class="item-bd">
                      <h3 class="project-name-2">后台开发(PHP)</h3>
                      <div class="div-item">
                        <h3 class="project-des">【项目简介】</h3>
                        <p class="item-project-des">
                          <a href="https://baike.baidu.com/item/%E4%B9%90%E5%BA%97%E4%BA%91" target="_blank"
                             title="点击查看->乐店云百度百科">乐店云</a>是一个专门为商户提供新零售智慧店铺解决方案的<a href="https://www.ledianyun.com/"
                                                                                   target="_blank" title="乐店云官网">一站式小程序生成平台</a>。项目主要采用PHP+Phalcon+Mysql框架，包含分销、砍价、拼团等营销以及基础的商城功能。
                        </p>
                      </div>
                      <div class="div-item">
                        <h3 class="project-des">【工作职责】</h3>
                        <ul class="section-content">
                          <li>负责拼团功能开发，该功能主要涉及用户与用户共同下单逻辑，需要保证在库存无误的情况下，实现多用户订单的提交与交易的正常进行</li>
                          <li>负责官网的开发以及官网搜索引擎优化</li>
                        </ul>
                      </div>
                    </div>
                  </li>
                </ol>
              </li>
            </ol>
          </div>

          <!--经历:伴知旅行-->
          <div class="item">
            <header class="item-hd">
              <h3 class="item-name">河南伴知旅行网络科技有限公司(郑州)</h3>
              <span class="item-time">2017.07 至 2017.12</span>
              <a class="btn item-more" href="https://baike.baidu.com/item/%E4%BC%B4%E7%9F%A5%E6%97%85%E8%A1%8C"
                 title="点击查看->伴知旅行百度百科">工作</a>
            </header>
            <ol class="item-project">
              <li class="project-1">
                <h3 class="project-name">伴知旅行</h3>
                <ol>
                  <li class="project-2">
                    <div class="item-bd">
                      <h3 class="project-name-2">伴知旅行Android APP</h3>
                      <div class="div-item">
                        <h3 class="project-des">【项目简介】</h3>
                        <p class="item-project-des">
                          <a href="https://baike.baidu.com/item/%E4%BC%B4%E7%9F%A5%E6%97%85%E8%A1%8C"
                             target="_blank" title="点击查看->伴知旅行百度百科">伴知旅行</a>是一个旅行社交分享社区<a
                          href="https://itunes.apple.com/cn/app/banzhi/id1281393616?mt=8" target="_blank"
                          title="点击进入->苹果App Store查看伴知旅行APP">APP</a>，它为每一个旅行者和当地人提供分享与交流的空间。旨在帮助旅行者的在旅行中结识到更多的朋友，让旅行者能够深入了解目的地的特色文化。主要提供：旅行结伴、旅行发现、知伴服务等服务
                        </p>
                      </div>
                      <div class="div-item">
                        <h3 class="project-des">【工作职责】</h3>
                        <ul class="section-content">
                          <li>负责团队基础技术支撑，包含构建流程、工具包、新技术探索等</li>
                          <li>制定APP开发规划，快速迭代、统一代码规范</li>
                          <li>主导和开发团队快速完成Android APP</li>
                          <li>协助完成部分Java API开发与维护</li>
                          <li>设计和开发项目底层框架，通过对工具及项目封装，解决开发过程中效率低的问题</li>
                        </ul>
                      </div>
                    </div>

                  </li>

                </ol>
              </li>
            </ol>
          </div>

          <!--经历:在校-->
          <div class="item">
            <header class="item-hd">
              <h3 class="item-name">豆芽科技工作室</h3>
              <span class="item-time">2015.08 ~ 2017.08</span>
              <a class="btn item-more" href="http://www.ztbu.edu.cn/" title="河南理工大学万方科技学院官网">在校</a>
            </header>
            <div class="item-bd">
              <p class="item-des">在校期间创建工作室，担任技术总监主导和带领朋友创业，工作室曾服务于：<span style="font-weight: bold">高校、企业及个人</span>，部分项目如下：
              </p>
              <ul class="section-content">
                <li><a href="http://www.ztbu.edu.cn/tw" title="点击进入->校团委官网">校团委官网</a> 校方组织比赛，胜出团队有报酬开发并维护团委官网</li>
                <li><a href="https://www.beious.com/" title="点击进入->贝欧名邸官网">贝欧名邸家具</a> 湖南客户公司商城系统</li>
                <li><a href="https://android.myapp.com/myapp/detail.htm?apkName=com.fendoumao.waimai"
                       title="点击查看->奋斗猫APP">奋斗猫APP</a>
                  西安客户公司APP外卖点餐系统
                </li>
                <li>
                  <a href="https://baike.baidu.com/item/%E5%A5%8B%E6%96%97%E7%8C%AB" title="点击查看->奋斗猫百度百科">奋斗猫全网优化</a>
                  奋斗猫全网优化项目包含搜索引擎优化（SEO）
                </li>
              </ul>
            </div>
          </div>
        </div>

      </section>
    </div>
    <div class="content-right">
      <section class="skill">
        <header class="section-hd">
          <span class="section-title-l"></span>
          <h2 class="section-title">技能</h2>
          <span class="section-title-r"></span>
        </header>
        <div class="section-bd">

          <!--技能:WEB后端开发-->
          <div class="item">
            <header class="item-hd">
              <span class="item-time">WEB后端开发</span>
              <a class="btn item-more">熟练掌握</a>
            </header>
            <div class="item-bd">
              <ul class="section-content">
                <li>两年后端应用Java、PHP实际开发经验，掌握Java面向对象思想编程</li>
                <li>熟练使用Spring Boot、SpringMVC等主流框架，熟悉Restful 风格API设计</li>
                <li>熟练使用数据库操作框架Hibernate JPA，掌握SQL语句增删改查</li>
                <li>熟练使用Websocket，并使用websocket进行服务端与客户端实时数据传输</li>
                <li>熟练使用Jwt等用户鉴权产品</li>
                <li>熟悉API开发基本流程，熟悉Restful 风格API设计</li>
                <li>熟练使用非关系型数据库Redis、MongoDB等，有Redis实际项目开发使用经验</li>
                <li>熟练使用消息中间件Rabbit MQ、kafka等开源中间件，有Rabbit MQ实际项目开发使用经验</li>
                <li>了解Spring cloud，正学习Spring cloud在企业大型应用中的应用，以及大型应用的微服务化及服务治理知识学习</li>
                <li>有金融交易、区块链及数字货币行业独立工作经验</li>
              </ul>
            </div>
          </div>

          <!--React-->
          <div class="item">
            <header class="item-hd">
              <span class="item-time">数据库</span>
              <a class="btn item-more">熟练掌握</a>
            </header>
            <div class="item-bd">
              <ul class="section-content">
                <li>熟悉关系型数据库技术，熟练使用关系型数据库Mysql、Oracle</li>
                <li>熟悉非关系型数据库技术，熟练使用非关系型数据库Nosql：Redis</li>
                <li>熟练使用Hibernate JPA，了解 MyBatis、JDBC等数据库操作框架使用</li>
                <li>了解分布式数据库及Mycat中间件，并正致力于提高分布式数据库能力和对于数据库高并发高可用的知识储备</li>
              </ul>
            </div>
          </div>

          <!--服务器|架构-->
          <div class="item">
            <header class="item-hd">
              <span class="item-time">服务器|架构</span>
              <a class="btn item-more">熟练掌握</a>
            </header>
            <div class="item-bd">
              <ul class="section-content">
                <li>熟练掌握Nginx、Tomcat、Apache服务器使用</li>
                <li>熟练掌握常用软件（MySQL、Redis、Rabbit MQ等）在服务器的搭建与使用</li>
                <li>熟练使用Centos(Linux)云服务器并掌握线上环境和应用的部署</li>
                <li>了解Docker使用及Docker应用部署</li>
                <li>熟悉微服务、高并发、高可用集群服务端架构</li>
                <li>熟练掌握Git、Github、gradle、maven等工具使用</li>
              </ul>
            </div>
          </div>

          <!--WEB前端开发-->
          <div class="item">
            <header class="item-hd">
              <span class="item-time">WEB前端开发</span>
              <a class="btn item-more">掌握</a>
            </header>
            <div class="item-bd">
              <ul class="section-content">
                <li>有一年以上Android原生开发经验，熟练掌握使用Java SE开发Android原生APP</li>
                <li>熟悉前端技术HTML、VUE、JS、CSS、Flutter，有实际项目中的前端开发、维护经验</li>
                <li>掌握网页重构所需的CSS、SCSS</li>
                <li>掌握前端流行框架Vue</li>
                <li>熟知JS基本语法与知识，熟悉JS语法</li>
                <li>熟练使用Websocket，并使用其进行服务端与客户端实时数据传输</li>
                <li>熟练使用Tradingview，使用Tradingview进行K线展示</li>
              </ul>
            </div>
          </div>

          <!--区块链-->
          <div class="item">
            <header class="item-hd">
              <span class="item-time">区块链</span>
              <a class="btn item-more">熟悉</a>
            </header>
            <div class="item-bd">
              <ul class="section-content">
                <li>熟练掌握以太坊链上操作</li>
                <li>熟悉以太坊DAPP开发；了解EOS公链DAPP开发</li>
                <li>熟练掌握数字钱包、加密货币、交易所开发流程</li>
                <li>两年数字货币交易所系统开发经验，有区块链智能合约、链上交互开发经验</li>
              </ul>
            </div>
          </div>

          <!--Golang-->
          <div class="item">
            <header class="item-hd">
              <span class="item-time">Golang</span>
              <a class="btn item-more">熟悉</a>
            </header>
            <div class="item-bd">
              <ul class="section-content">
                <li>熟悉Golang基本语法与标准库</li>
                <li>用Golang开发过小型项目服务</li>
              </ul>
            </div>
          </div>

          <!--独立开发-->
          <div class="item">
            <header class="item-hd">
              <span class="item-time">独立开发</span>
            </header>
            <div class="item-bd">
              <ul class="section-content">
                <li>有独自主导并负责的项目开发经验，在项目中可进行独立开发</li>
                <li>有良好的编码习惯与编程思想，学习能力强，可快速学习新技术，对新技术、好技术热爱</li>
                <li>工作稳定性高，对公司负责，有一定的项目管理经验，有创业经历</li>
              </ul>
            </div>
          </div>

          <!--其它-->
          <div class="item">
            <header class="item-hd">
              <span class="item-time">其它</span>
            </header>
            <div class="item-bd">
              <ul class="section-content">
                <li>掌握Java、PHP、Golang、C、Git、Docker、硬件开发</li>
                <li>本科毕设：智能家电物联网控制系统</li>
                <li>资深Mac & JetBrains用户</li>
              </ul>
            </div>
          </div>
        </div>
      </section>

      <!--开源项目-->
      <section class="project">
        <header class="section-hd">
          <span class="section-title-l"></span>
          <h2 class="section-title">开源项目</h2>
          <span class="section-title-r"></span>
        </header>
        <div class="section-bd">
          以下是我的开源项目与学习总结，细节请点击链接查看文档（其他项目开发中，尚未开源，敬请期待）

          <!--项目:博客-->
          <div class="item">
            <header class="item-hd">博客/Github</header>
            <div class="item-bd">
              <ul>
                <li>
                  <a href="https://blog.csdn.net/qq_28505809" target="_blank">CSDN博客</a>
                </li>
                <li>
                  <a href="https://github.com/GuoyiZhang" target="_blank">Github</a>
                </li>
                <li>
                  <a href="http://www.guoyi.pro" target="_blank">个人网站主页</a>
                </li>
              </ul>
            </div>
          </div>

          <!--项目:WEB前端-->
          <div class="item">
            <header class="item-hd">WEB前端</header>
            <div class="item-bd">
              <ul>
                <li>
                  <a href="https://github.com/GuoyiZhang/013-HtmlWeb-Js_KLine">K线</a> JS实现的K线展示组件，项目基于开源项目改造
                </li>
                <li>
                  <a href="https://github.com/GuoyiZhang/077-Android-ListeningLove">乐听乐爱</a>
                  全网音乐搜索与播放APP，可播放下载酷狗、QQ音乐、网易云等音乐库资源，此项目仅用于学习交流
                </li>
              </ul>
            </div>
          </div>
        </div>
      </section>

      <!--奖项/证书-->
      <section class="prize">
        <header class="section-hd">
          <span class="section-title-l"></span>
          <h2 class="section-title">奖项/证书</h2>
          <span class="section-title-r"></span>
        </header>
        <div class="section-bd">

          <!--技能:WEB后端开发-->
          <div class="item">
            <header class="item-hd">
              <span class="item-time">获奖经历</span>
            </header>
            <div class="item-bd">
              <ul class="section-content">
                <li>2017年9月获得Ican创新设计大赛三等奖</li>
                <li>2017年7月获得智能互联创新大赛二等奖</li>
                <li>2016年获得校网页设计大赛三等奖</li>
                <li>2016年获得计算机二级证书</li>
              </ul>
            </div>
          </div>
        </div>
      </section>

      <!--致谢-->
      <section class="thanks">
        <header class="section-hd">
          <span class="section-title-l"></span>
          <h2 class="section-title">致谢</h2>
          <span class="section-title-r"></span>
        </header>
        <div class="section-bd">
          <!--技能:WEB后端开发-->
          <div class="item">
            <h2 style="font-weight: bold;line-height: 24px;margin-top: 10px">
              感谢您在百忙之中阅读这份履历，诚挚的期望能得到面试的机会，希望有荣幸能为公司效力！再次致以我最诚挚的谢意！！</h2>
          </div>
        </div>
      </section>

    </div>
  </div>
</template>

<script>
    import $ from 'jquery'

    export default {
        name: 'Content',
        components: {},
        data() {
            return {
                msg: 'Welcome to Your Vue.js App'
            }
        },
        mounted() {
            $(document).ready(function () {
                if ($('ol:first').css('list-style-type') == 'none') { /* For IE6/7 only. */
                    $('ol ol').each(function (i, ol) {
                        ol = $(ol);
                        var level1 = ol.closest('li').index() + 1;
                        ol.children('li').each(function (i, li) {
                            li = $(li);
                            var level2 = level1 + '.' + (li.index() + 1);
                            li.prepend('<span>' + level2 + '</span>');
                        });
                    });
                }
            });
        }
    }
</script>
