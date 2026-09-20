<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2jye-1ly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c2jye-1ly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:vip-consume-outline" {...props}></Icon>
