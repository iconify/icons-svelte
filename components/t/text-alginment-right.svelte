<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5vx6_pxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="t5vx6_pxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:text-alginment-right" {...props}></Icon>
