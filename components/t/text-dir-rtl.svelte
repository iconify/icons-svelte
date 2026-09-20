<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dv21g9bkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dv21g9bkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:text-dir-rtl" {...props}></Icon>
