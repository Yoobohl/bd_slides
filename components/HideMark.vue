<template>

    <v-switch>
        <template #1>
            <div>
                <h1 v-mark="{ at: 1, color: 'red', type: 'crossed-off' }">
                    进口
                </h1>
            </div>
        </template>
        <template #2>
            <h1>
                国产
            </h1>
        </template>
    </v-switch>
</template>

<script setup>
setInterval(() => {
    console.log(document.URL)
}, 700)
</script>
