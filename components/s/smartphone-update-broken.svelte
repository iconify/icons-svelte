<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/ggvf3nb4s.css';
import '../../css/c/cw0dg-bgf.css';
import '../../css/e/erekrcbav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ggvf3nb4s"/><path class="cw0dg-bgf"/><path class="erekrcbav"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:smartphone-update-broken" {...props}></Icon>
