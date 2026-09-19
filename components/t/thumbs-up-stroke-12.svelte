<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/l/lofmxcb-i.css';
import '../../css/e/e-dxg-xyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<g class="h01tyzbfu"><path class="lofmxcb-i"/><rect class="e-dxg-xyc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:thumbs-up-stroke-12" {...props}></Icon>
