<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/w/wqss8ttiy.css';
import '../../css/g/gw-3o2bdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="wqss8ttiy"/><path class="gw-3o2bdq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:sun" {...props}></Icon>
