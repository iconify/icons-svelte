<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t0z8m6xkt.css';
import '../../css/z/zds3n0a5a.css';
import '../../css/u/uamja8bzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="t0z8m6xkt"/><path class="zds3n0a5a"/><path class="uamja8bzk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:star-half-2-duo" {...props}></Icon>
