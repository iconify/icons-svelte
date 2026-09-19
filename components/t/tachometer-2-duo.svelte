<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p8ebzs-6d.css';
import '../../css/a/azwpubnof.css';
import '../../css/o/otgnaobru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="p8ebzs-6d"/><path class="azwpubnof"/><path class="otgnaobru"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tachometer-2-duo" {...props}></Icon>
