<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/yi_7vme2b.css';
import '../../css/w/w3a9vb0vh.css';
import '../../css/g/gvtuoyesg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="yi_7vme2b"/><path class="w3a9vb0vh"/><path clip-rule="evenodd" class="gvtuoyesg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:sweating2x-outline" {...props}></Icon>
