<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/iwqi-5bwl.css';
import '../../css/w/wz5f-bcbc.css';
import '../../css/y/yiu_zb82h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="iwqi-5bwl"/><path clip-rule="evenodd" class="wz5f-bcbc"/><path clip-rule="evenodd" class="yiu_zb82h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:volume-up-duotone" {...props}></Icon>
