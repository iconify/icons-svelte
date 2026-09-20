<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg-gktmdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yg-gktmdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:save-outline" {...props}></Icon>
