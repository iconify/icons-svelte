<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k0v0id9pz.css';
import '../../css/y/y_ekn01od.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":301,"height":201};
const content = `<g class="ft5dv1b6b"><path class="k0v0id9pz"/><path class="y_ekn01od"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cif:ua" {...props}></Icon>
