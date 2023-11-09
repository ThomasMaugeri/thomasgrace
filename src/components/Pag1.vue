<script>

</script>

<template>
  <div class="header">
    <div class="leftheader">
       <span>Grace</span> 
        <div class="rightheader">
            <ul>
                <li> <div class="lingua"></div> language</li>
                <li> <div class="comprare"></div>buy</li>
                <li> <div class="account"></div>profile</li>
                <li> <div class="shop"></div>shop</li>
                <li> <div class="menu"></div>menu</li>
                <li><div class="home"></div>home</li>
            </ul>
        </div>
    </div>
  </div>
</template>

<style scoped>
.header {
  display: flex;
  padding: 40px 20px 40px 20px;
}
.leftheader {
    display: flex;
    font-size: 30px;
    align-items: center;
}

.rightheader {
    background-color: aquamarine;
    display: flex;
    justify-content: flex-end;
}
</style>