<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyux0j27g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yyux0j27g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:up-right-and-down-left-from-center" {...props}></Icon>
