<template>
    <div class="RMContainer">
        <div class="bg"></div>
        <div class="data">
            <p>Total collateral</p>
            <p>$1916.54</p>
        </div>
        <div class="data">
            <p>Free Margin</p>
            <p>$952.73</p>
        </div>
        <div class="data">
            <p>Leverage</p>
            <p>2.95X</p>
        </div>
        <div class="data">
            <p>Max Leverage</p>
            <p>10X</p>
        </div>
        <div class="data">
            <p>Margin Fraction</p>
            <p>33.82%</p>
        </div>
        <div class="data">
            <p>Total Notionla Postion</p>
            <p>$3998.05</p>
        </div>
        <div class="data">
            <p>Unrelized PNL</p>
            <p>$0</p>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'RightBottom'
    }
</script>

<style scoped>
.RMContainer{
    display: flex;
    flex-direction: column;
    position: relative;
    height: 100%;
        padding-left: 22px;
    padding-right: 22px;
}
.bg{
    background-image: url('../../asset/BackgroundPattern.png');
    background-repeat: no-repeat;
    background-position-x: 100%;
    background-position-y: 100%;
    width: 100%;
    height: 100%;
    position: absolute;
    top: 0;
    left: 0;
}
.data{
    background:transparent;
    z-index: 1;
    /* border: 1px solid green; */
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    width: 100%;
    height: auto;
    margin-top: 16px;
}
.data p {
    background:transparent;
    font-size: 16px;
}

.data p:nth-child(1){
    color: #6E798F;
}
</style>