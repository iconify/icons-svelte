<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yipja7bqc.css';
import '../../css/n/ncw19pbwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yipja7bqc"/><path class="ncw19pbwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:window" {...props}></Icon>
