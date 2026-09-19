<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bcvdmjbdg.css';
import '../../css/n/ni8mupnkh.css';
import '../../css/j/jig8hfb4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bcvdmjbdg"/><path class="ni8mupnkh"/><path class="jig8hfb4h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:truck-solid" {...props}></Icon>
