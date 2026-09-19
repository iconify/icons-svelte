<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/pcnhie19y.css';
import '../../css/e/esoc3gbtn.css';
import '../../css/n/nyouw_b1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path clip-rule="evenodd" class="pcnhie19y"/><path class="esoc3gbtn"/><path class="nyouw_b1f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:scroll-text" {...props}></Icon>
