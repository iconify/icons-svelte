<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw068u8kk.css';
import '../../css/w/wx-066bcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gw068u8kk"/><path class="wx-066bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:transform-instructions" {...props}></Icon>
