<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo9hwmbwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vo9hwmbwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:search" {...props}></Icon>
