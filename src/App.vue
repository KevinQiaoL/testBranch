<template>
<div id="app">
    <a href="https://m.baidu.com" class="item">
        <div class="thumbnail">
            <img src="/img/qlc@2x.png" alt="">
        </div>
        <div class="info">
            <h1>趣乐彩</h1>
            <p>
                趣乐彩是一款为彩店业主提供包含开奖结果、创意海报、专家分析推荐等功能的彩票信息服务平台。趣乐彩提供包括双色球、福彩3D、大乐透、排列三/五、竞彩足球、竞彩篮球、传统足彩等福/体彩最全面及时的开奖信息... <span>查看更多&gt;</span>
            </p>
        </div>
    </a>
    <a class="item">
        <div class="thumbnail">
            <img src="/img/yntc@2x.png" alt="">
        </div>
        <div class="info">
            <h1>云南体彩</h1>
            <p>
                公益体彩 乐善人生。云南体彩app是云南体彩官方应用。提供包括双色球、福彩3D、大乐透、排列三/五、竞彩足球、竞彩篮球、传统足彩等福/体彩最全面及时的开奖信息。体彩资讯，视频，专家晒单，即时聊天等。
                <span class="warning">未授权，不做跳转</span>
            </p>
        </div>
    </a>
    <a class="item">
        <div class="thumbnail">
            <img src="/img/zqss@2x.png" alt="">
        </div>
        <div class="info">
            <h1>足球赛事展示</h1>
            <p>
                用于体彩店电子屏展示。<br>
                提供 竞彩足球/北京单场/传统足彩的比赛对阵，赔率分析等
                <span class="warning">立即跳转&gt;</span>
            </p>
        </div>
    </a>
</div>
</template>
<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
@Component
export default class App extends Vue {}
</script>
<style lang="scss">
* {
    box-sizing: border-box;
    -webkit-tap-highlight-color: transparent;
    -webkit-touch-callout: none;
}
:root{
    --color-dark: #333;
    --color-danger: #e82c2b;
    --color-warning: #f90;
    --color-success: #f90;
    --color-info: #1989fa;
    --color-medium: #666;
    --color-muted: #999;
    --color-line: #eee;
}
html{
    width: 100%;
    height: 100%;
    text-size-adjust: 100%;
    --live-safe-area-top: env(safe-area-inset-top);
    --live-safe-area-bottom: env(safe-area-inset-bottom);
    --live-safe-area-left: env(safe-area-inset-left);
    --live-safe-area-right: env(safe-area-inset-right);
}
body{
    margin: 0;
}
.item{
    display: block;
    margin: 12px;
    border-radius: 4px;
    box-shadow: 0 0 4px rgba(0, 0, 0, .1);
    text-decoration: none;
    .thumbnail{
        width: 100%;
        height: 33vh;
        border-top-left-radius: 4px;
        border-top-right-radius: 4px;
        overflow: hidden;
        img{
            width: 100%;
            height: 100%;
            display: block;
            object-fit: cover;
            object-position: top;
        }
    }
    .info {
        padding: 12px;
        h1{
            margin: 0;
            height: 25px;
            font-size: 16px;
            color: var(--color-dark);
        }
        p{
            margin: 5px 0 0;
            font-size: 14px;
            line-height: 20px;
            color: var(--color-muted);
            span{
                color: var(--color-info);
            }
        }
    }
}
</style>

