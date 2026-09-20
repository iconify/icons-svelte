<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/ay8tbubjq.css';
import '../../css/s/sfu0pxbzr.css';
import '../../css/n/n5o__tdls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ay8tbubjq"/><path class="sfu0pxbzr"/><path class="n5o__tdls"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:wifi-filled" {...props}></Icon>
