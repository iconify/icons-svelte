<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt3b0obzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jt3b0obzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tradingview-dark" {...props}></Icon>
