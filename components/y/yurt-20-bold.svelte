<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mm5w_o49z.css';
import '../../css/f/f_tlp__ao.css';
import '../../css/u/us9cbxkls.css';
import '../../css/r/rdd2babaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mm5w_o49z"/><path class="f_tlp__ao"/><path class="us9cbxkls"/><path class="rdd2babaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:yurt-20-bold" {...props}></Icon>
