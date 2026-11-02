<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zszwr2big.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zszwr2big"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:vip-4-line" {...props}></Icon>
