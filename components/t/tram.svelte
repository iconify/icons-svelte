<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/pcg8mdk_e.css';
import '../../css/n/ngtd4hbhd.css';
import '../../css/o/o5czz65za.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pcg8mdk_e"/><path class="ngtd4hbhd"/><path class="o5czz65za"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:tram" {...props}></Icon>
