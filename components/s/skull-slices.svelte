<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee_pagbuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ee_pagbuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:skull-slices" {...props}></Icon>
