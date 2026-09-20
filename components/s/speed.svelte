<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/i/i3w0-bidx.css';
import '../../css/b/bjw6ntbil.css';
import '../../css/t/toz5ulbud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="i3w0-bidx"/><path class="bjw6ntbil"/><path class="toz5ulbud"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:speed" {...props}></Icon>
