<template>
    <div class="hex">
        <div class="left"></div>
        <div class="mid"></div>
        <div class="right"></div>
    </div>
</template>
<script>
export default {
  name: 'Hexagon'
}
</script>

<style scoped>

.left {
    float: left;
    border-right: 30px solid #6C6;
    border-top: 52px solid transparent;
    border-bottom: 52px solid transparent
}
.mid {
    float: left;
    width: 60px;
    height: 104px;
    background-color: #6C6;
}
.right {
    float: left;
    border-left: 30px solid #6C6;
    border-top: 52px solid transparent;
    border-bottom: 52px solid transparent;
}
</style>