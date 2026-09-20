<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdo6hzbjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hdo6hzbjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:star3" {...props}></Icon>
