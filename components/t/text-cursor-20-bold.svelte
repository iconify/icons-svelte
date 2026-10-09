<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jijaykbcd.css';
import '../../css/u/uylaeij1i.css';
import '../../css/y/y1e_v1sal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jijaykbcd"/><path class="uylaeij1i"/><path class="y1e_v1sal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:text-cursor-20-bold" {...props}></Icon>
