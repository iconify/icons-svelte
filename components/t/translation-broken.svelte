<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lq7nc17nr.css';
import '../../css/p/px3i7t95o.css';
import '../../css/h/h_tsn8bxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lq7nc17nr"/><path class="px3i7t95o"/><circle class="h_tsn8bxt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:translation-broken" {...props}></Icon>
