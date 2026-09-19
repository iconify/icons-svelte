<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kfoxa_z9z.css';
import '../../css/k/kvdaehorh.css';
import '../../css/y/ydmyb5ahc.css';
import '../../css/s/s7ii38vjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="kfoxa_z9z"/><path class="kvdaehorh"/><path class="ydmyb5ahc"/><path class="s7ii38vjp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:waves" {...props}></Icon>
