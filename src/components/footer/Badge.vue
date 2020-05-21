<!-- Github 徽章 https://shields.io/ -->

<template>
    <div>
        <!-- license -->
        <a href="https://github.com/KinFan/KinFan/blob/master/LICENSE" target="_blank">
            <img alt="GitHub" src="https://img.shields.io/github/license/KinFan/KinFan">
        </a>
        <!-- 版本号 -->
        <a href="https://github.com/KinFan/KinFan/" target="_blank">
            <img alt="GitHub package.json version" src="https://img.shields.io/github/package-json/v/KinFan/KinFan">
        </a>
        <!-- stars -->
        <a href="https://github.com/KinFan/KinFan/" target="_blank">
            <img alt="GitHub stars" src="https://img.shields.io/github/stars/KinFan/KinFan">
        </a>
        <!-- fork -->
        <a href="https://github.com/KinFan/KinFan/fork" target="_blank">
            <img alt="GitHub forks" src="https://img.shields.io/github/forks/KinFan/KinFan">
        </a>
        <!-- 下载 -->
        <a href="https://github.com/KinFan/KinFan/releases" target="_blank">
            <img alt="GitHub All Releases" src="https://img.shields.io/github/downloads/KinFan/KinFan/total">
        </a>
    </div>
</template>

<script lang="ts">
    import {Component, Vue} from 'vue-property-decorator';

    @Component({})
    export default class Badge extends Vue {
    }
</script>

<style scoped lang="scss">
    a {
        margin: 0.5em;
    }
</style>
