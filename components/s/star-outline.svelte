<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0kh8pbwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y0kh8pbwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:star-outline" {...props}></Icon>
