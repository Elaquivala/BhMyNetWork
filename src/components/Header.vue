<template>
    <header id="header">
        <div id="left">
            <img id="img-vue" src="../assets/images/mynetwork.png" />
            <h4></h4>
           
        </div>
        <div id="right">
        </div>
    </header>
</template>

<script setup>

</script>

<style scoped>

#header {
    width: 100%;
    height: 10vh;
    background-color: #ffffff;
    display: flex;
    flex-direction: row;
}

#left {
    width: 50%;
    height: 100%;
    display: flex;
    flex-direction: row;
    align-items: center;
    padding-left: 30px;
    color: rgb(0, 0, 0)
}

#right {
    width: 50%;
    height: 100%;
    display: flex;
    flex-direction: row-reverse;
    align-items: center;
    padding-right: 20px;
    color: rgb(0, 0, 0);
    text-transform: uppercase;
}



#img-vue {
    width: 300px;
    height: 100px;
    margin-right: 10px;
 

}

</style>