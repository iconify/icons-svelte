<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/cfkicbk9n.css';
import '../../css/w/wnxmdjbom.css';
import '../../css/p/pokq2rrtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="cfkicbk9n"/><path class="wnxmdjbom"/><path class="pokq2rrtg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:text-split-duo" {...props}></Icon>
