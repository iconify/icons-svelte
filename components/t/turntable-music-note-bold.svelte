<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/uw2l8abgq.css';
import '../../css/f/fxs8d8bzw.css';
import '../../css/e/e3_kkkb-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="uw2l8abgq"/><path class="fxs8d8bzw"/><path clip-rule="evenodd" class="e3_kkkb-z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:turntable-music-note-bold" {...props}></Icon>
