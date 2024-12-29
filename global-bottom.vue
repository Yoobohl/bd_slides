<!-- 一个显示页数的页脚示例 -->
<template>
    <footer v-if="$nav.currentLayout !== 'cover'" class="absolute bottom-0 left-0 right-0 p-2">
        <span style="font-size: xx-small;">[{{ $nav.clicks }}]</span>{{ $nav.currentPage }}/ {{ $nav.total }}
    </footer>
</template>