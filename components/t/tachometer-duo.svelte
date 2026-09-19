<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p8ebzs-6d.css';
import '../../css/m/mpj41y35s.css';
import '../../css/v/vhsahq0yk.css';
import '../../css/i/iy5jtk2cn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="p8ebzs-6d"/><path class="mpj41y35s"/><path class="vhsahq0yk"/><path class="iy5jtk2cn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tachometer-duo" {...props}></Icon>
