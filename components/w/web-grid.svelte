<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yawc-nbwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yawc-nbwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:web-grid" {...props}></Icon>
