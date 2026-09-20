<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rjoql5gzl.css';
import '../../css/i/izq59sb8f.css';
import '../../css/p/pqt-l0b-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rjoql5gzl"/><rect class="izq59sb8f"/><path class="pqt-l0b-z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:server-light" {...props}></Icon>
