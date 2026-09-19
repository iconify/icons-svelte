<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p8ebzs-6d.css';
import '../../css/k/kcc_vbbob.css';
import '../../css/y/y15340b1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="p8ebzs-6d"/><path class="kcc_vbbob"/><path class="y15340b1j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tachometer-5-duo" {...props}></Icon>
