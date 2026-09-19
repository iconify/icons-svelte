<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6eyopbhz.css';
import '../../css/d/dxpxq77kj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6eyopbhz"/><path class="dxpxq77kj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:wind" {...props}></Icon>
