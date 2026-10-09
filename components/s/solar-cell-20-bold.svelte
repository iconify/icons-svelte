<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9svkd5iy.css';
import '../../css/m/m5wg2ub_n.css';
import '../../css/l/lgigiqbja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k9svkd5iy"/><path class="m5wg2ub_n"/><path class="lgigiqbja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-cell-20-bold" {...props}></Icon>
