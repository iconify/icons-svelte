<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mbit45gps.css';
import '../../css/b/bzb5x4zov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":301,"height":201};
const content = `<g class="ft5dv1b6b"><path class="mbit45gps"/><path class="bzb5x4zov"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cif:vn" {...props}></Icon>
