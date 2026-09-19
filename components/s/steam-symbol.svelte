<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd_1y0b4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="zd_1y0b4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:steam-symbol" {...props}></Icon>
