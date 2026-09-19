<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1hd5ebhz.css';
import '../../css/l/lyd-xwqcp.css';
import '../../css/n/ndnl__jzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p1hd5ebhz"/><path class="lyd-xwqcp"/><path class="ndnl__jzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:text-annotation-toggle" {...props}></Icon>
