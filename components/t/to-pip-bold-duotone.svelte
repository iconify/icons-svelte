<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cxs5opefl.css';
import '../../css/p/p35oimbbv.css';
import '../../css/q/qrk41hb3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cxs5opefl"/><path class="p35oimbbv"/><path class="qrk41hb3l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:to-pip-bold-duotone" {...props}></Icon>
