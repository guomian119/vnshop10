<template>
         <div class="site-header" style="clear:both;">
        <div class="container">
            <div class="header-logo">
                <a href="index.php" title="小米官网"><img src="/static/img/vn-logo.png" /></a>
            </div>
            <div class="header-nav">
                <ul class="nav-list">
                    <li class="nav-category">
                        <a class="btn-category-list" href="catalog.php" style="display:none;">全部商品分类</a>
                    </li>
                    <li class="nav-item">
                        <a class="link" href="category.php?id=76"><span>电子产品</span></a>
                        <div class='item-children'>
                            <div class="container">
                                <ul class="children-list clearfix">
                                    <li class="first">
                                        <div class="figure figure-thumb">
                                            <a href="goods.php?id=27"><img src="" alt="小米电视2 40英寸"></a>
                                        </div>
                                        <div class="title"><a href="goods.php?id=27">小米电视2 40英寸</a></div>
                                        <p class="price">2200<em>元</em>元</p>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </li>
                </ul>
            </div>
            <!-- <div class="container-user"> -->
            <div class="topbar-cart" id="ECS_CARTINFO">
                <a class="cart-mini " href="flow.php">
                    <i class="iconfont">&#xe60c;</i> 购物车
                    <span class="mini-cart-num J_cartNum" id="hd_cartnum">(0)</span>
                </a>
            </div>
            <div class="topbar-info J_userInfo" id="ECS_MEMBERZONE">
                <a class="link" href="user.php" rel="nofollow">登录</a>
                <span class="sep">|</span>
                <a class="link" href="user.php?act=register" rel="nofollow">注册</a>
            </div>
            <!-- </div> -->
        </div>
        <div id="J_navMenu" class="header-nav-menu" style="display: none;">
            <div class="container"></div>
        </div>
    </div>
</template>
<script>
    export default{

    }
</script>