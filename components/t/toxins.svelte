<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/y/yfht0cwhz.css';
import '../../css/a/ai3i-1iaj.css';
import '../../css/k/kvwgoxdqi.css';
import '../../css/f/fto0fpt6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path clip-rule="evenodd" class="yfht0cwhz"/><path class="ai3i-1iaj"/><path class="kvwgoxdqi"/><path class="fto0fpt6d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:toxins" {...props}></Icon>
