<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nn5c_ac-c.css';
import '../../css/a/a71n0cp7w.css';
import '../../css/n/nvedv7b7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nn5c_ac-c"/><path class="a71n0cp7w"/><path class="nvedv7b7x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:truck-line" {...props}></Icon>
