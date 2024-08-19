<template>
    <nav>
        <div>
            <div class="navbar-header">
                <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                </button>
                <a class="navbar-brand">
                    <img class="navbar-logo" src="@/assets/spLogo.png" alt="Joe's Sloppy Pizza" />
                </a>
            </div>

            <div class="collapse navbar-collapse" id="myNavbar">
                <ul class="nav navbar-nav">
                    <li class="active"><router-link v-bind:to="{ name: 'home' }">Home</router-link></li>
                    <li><router-link v-bind:to="{ name: 'about-us' }">About Us</router-link></li>
                    <li><router-link v-bind:to="{ name: 'order' }">Order Now</router-link></li>
                    <li><router-link v-bind:to="{ name: 'contact' }">Contact Us</router-link></li>
                </ul>
                <ul class="nav navbar-nav navbar-right">
                    <li><router-link v-bind:to="{ name: 'shopping-cart' }"><img class="navbar-brand"
                                src="@/assets/shopping-cart2.png" alt="shopping cart img"
                                style="width: 65px; height: 65px;"></router-link></li>
                    <li><router-link v-bind:to="{ name: 'login' }">Login</router-link></li>
                    <li><router-link v-bind:to="{ name: 'register' }">Register</router-link></li>
                </ul>
            </div>
        </div>
    </nav>
</template>

<script>

</script>

<style scoped>


</style>
