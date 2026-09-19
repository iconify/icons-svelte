<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/q/qoehezbdc.css';
import '../../css/b/b1_u0pbjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="qoehezbdc"/><path class="b1_u0pbjf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:settings" {...props}></Icon>
