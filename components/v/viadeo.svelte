<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv2331gbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="yv2331gbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:viadeo" {...props}></Icon>
