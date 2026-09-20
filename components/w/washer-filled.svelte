<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/ug_skfbsy.css';
import '../../css/f/fwknfdbgo.css';
import '../../css/l/ledwm5bxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ug_skfbsy"/><path class="fwknfdbgo"/><path clip-rule="evenodd" class="ledwm5bxp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:washer-filled" {...props}></Icon>
