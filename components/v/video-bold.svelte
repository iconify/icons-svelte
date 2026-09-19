<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b_anj2b6u.css';
import '../../css/b/bm7c4r5hg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><rect class="b_anj2b6u"/><path clip-rule="evenodd" class="bm7c4r5hg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:video-bold" {...props}></Icon>
