<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtowsomii.css';
import '../../css/f/f6r4u0dcm.css';
import '../../css/p/pd1h9oded.css';
import '../../css/e/eo6qbob6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="f6r4u0dcm"/><path class="pd1h9oded"/><path class="eo6qbob6h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:window-collapse-right" {...props}></Icon>
