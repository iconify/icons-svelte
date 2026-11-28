<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/if_fr7tub.css';
import '../../css/k/kcc_36bdy.css';
import '../../css/k/ke6fezb3o.css';
import '../../css/r/rzbp2-b8z.css';
import '../../css/f/f46f54b3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="if_fr7tub"/><path class="kcc_36bdy"/><path class="ke6fezb3o"/><path class="rzbp2-b8z"/><path class="f46f54b3m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:scatter-chart" {...props}></Icon>
