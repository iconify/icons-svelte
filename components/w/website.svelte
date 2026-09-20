<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wptum8b_n.css';
import '../../css/x/x7spcd5gw.css';
import '../../css/r/r_u2rg8xx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="wptum8b_n"/><path class="x7spcd5gw"/><path class="r_u2rg8xx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:website" {...props}></Icon>
