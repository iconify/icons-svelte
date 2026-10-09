<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtc4_gbjh.css';
import '../../css/y/y4wwydbht.css';
import '../../css/y/yctemwfli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xtc4_gbjh"/><path class="y4wwydbht"/><path class="yctemwfli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-tile-20" {...props}></Icon>
