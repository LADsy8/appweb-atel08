<script setup lang="ts">
/// <reference types="../../node_modules/.vue-global-types/vue_3.5_false.d.ts" />
import type { TimelinePost } from '../posts';
defineProps<{
post: TimelinePost
}>()</script>
<template><li>
    <span>{{ post.title }}</span>&nbsp;|&nbsp;
    <span>{{ post.created.toFormat("d MMM") }}</span>
    </li></template>
<style></style>