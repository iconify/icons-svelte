<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yehyu3l8d.css';
import '../../css/m/m6mu15bsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yehyu3l8d"/><path class="m6mu15bsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tide-high-48-bold" {...props}></Icon>
