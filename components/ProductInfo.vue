<template>
    <div class="wrapper">
        <div class="block block1">
            <span>20 纳秒</span>
            <span style="font-size: xx-small;">授时精度</span>

        </div>
        <div class="block block2">
            <span>10 年</span>
            <span style="font-size: xx-small;">使用寿命</span>

        </div>
        <div class="block block3">
            <img src="/images/beidou_rendering.png" alt="">
        </div>
    </div>

</template>

<style>
.wrapper {
    display: grid;
    row-gap: 20px;
    column-gap: 20px;
    grid-auto-flow: row;
}

.block {
    background-color: aquamarine;
    padding: 10px;
    border-radius: 10px;
    display: flex;
    flex-direction: column;
    align-items: center;
}

.block1 {
    grid-column: 1/2;
    grid-row: 1/2;
}

.block2 {
    grid-column: 3/4;
    grid-row: 3/4;
}

.block3 {
    grid-column: 2/3;
    grid-row: 2/3;
    padding: 0;
    height: 100px;
    width: 100px;
}
</style>