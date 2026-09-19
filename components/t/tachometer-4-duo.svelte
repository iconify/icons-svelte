<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p8ebzs-6d.css';
import '../../css/d/dt-an-o6a.css';
import '../../css/v/vpkmwzzxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="p8ebzs-6d"/><path class="dt-an-o6a"/><path class="vpkmwzzxi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tachometer-4-duo" {...props}></Icon>
