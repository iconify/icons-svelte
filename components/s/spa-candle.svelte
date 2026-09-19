<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3nk8bb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y3nk8bb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:spa-candle" {...props}></Icon>
