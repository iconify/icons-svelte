<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3xtuk_0z.css';
import '../../css/p/prq48dbgc.css';
import '../../css/q/qg63ysl4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="l3xtuk_0z"><path class="prq48dbgc"/><path class="qg63ysl4c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:volume-medium" {...props}></Icon>
