<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/x6scb8b-g.css';
import '../../css/j/j5zg0bc7u.css';
import '../../css/o/ocihuquga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="x6scb8b-g"/><path class="j5zg0bc7u"/><path class="ocihuquga"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:toggle-1-bold" {...props}></Icon>
