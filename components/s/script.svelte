<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxbhd888r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="wxbhd888r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:script" {...props}></Icon>
