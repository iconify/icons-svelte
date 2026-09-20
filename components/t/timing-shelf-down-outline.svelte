<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh16x0bfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yh16x0bfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:timing-shelf-down-outline" {...props}></Icon>
