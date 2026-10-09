<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eagfqob-p.css';
import '../../css/h/hx_d8fz_e.css';
import '../../css/c/cbwvap00w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="eagfqob-p"/><path class="hx_d8fz_e"/><path class="cbwvap00w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-cell-20" {...props}></Icon>
