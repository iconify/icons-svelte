<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/ut8cuhtwq.css';
import '../../css/k/kbs4yj5cx.css';
import '../../css/n/nzciehbug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ut8cuhtwq"/><path class="kbs4yj5cx"/><path class="nzciehbug"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:wallet3-filled" {...props}></Icon>
