<template>
    <div class="container">
        <div class="row">
            <div class="col-1">
                <h1><span>THE LATEST</span><br/>FURNITURE DESIGN</h1>
                <div  class="btn-background"/>
                <button>SHOP NOW ></button>
            </div>
            <div class="col-2">
                <img src="../assets/bg.jpg" alt='background'/>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name:'Home'
}
</script>

<style scoped>
.container{
    height: calc(100vh - 80px);
    background: #e8e9e9;
    width: 100%;
}
.row{
    min-height: 100%;
    background: #e8e9e9;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: space-between;
    align-items: center;
    padding: 0 5%;
}

.col-1{
    flex:2;
}

.col-2{
    flex:1;
}

h1{
    font-size: 6rem;
    color: #0a0101;
}

span{
    color: #3cbbad;
}

.btn-background{
    background: black;
    width: 162.39px;
    height: 48px;
    border-radius: 5px;
    z-index:-1;
    margin-top: 30px;
}

button{
    border: none;
    font-size: 1rem;
    background-color: #ffffff;
    padding: 15px 30px;
    border-radius: 5px;
    z-index: 1;
    position: relative;
    top:-55px;
    left:5px    
}
</style>