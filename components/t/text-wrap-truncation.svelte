<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3lph30dl.css';
import '../../css/v/vuc32ac1y.css';
import '../../css/l/luspzab5n.css';
import '../../css/l/ldm5tkdqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="vuc32ac1y"/><path class="luspzab5n"/><path class="ldm5tkdqi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:text-wrap-truncation" {...props}></Icon>
