<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-l1pd0_w.css';
import '../../css/q/q536fgb0l.css';
import '../../css/h/hy4c77bzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h-l1pd0_w"><path clip-rule="evenodd" class="q536fgb0l"/><path class="hy4c77bzt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:wallet-solid" {...props}></Icon>
