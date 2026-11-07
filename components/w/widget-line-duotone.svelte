<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/m1843wb_j.css';
import '../../css/v/v6paw-brs.css';
import '../../css/d/djqs5cxtc.css';
import '../../css/q/qlfd6-bzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="m1843wb_j"/><path class="v6paw-brs"/><path class="djqs5cxtc"/><path class="qlfd6-bzg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:widget-line-duotone" {...props}></Icon>
