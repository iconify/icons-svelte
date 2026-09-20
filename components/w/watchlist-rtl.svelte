<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thes92byx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="thes92byx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:watchlist-rtl" {...props}></Icon>
