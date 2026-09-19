<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/w8myxrsji.css';
import '../../css/f/fn6lbqmuk.css';
import '../../css/a/afy8xbjmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="w8myxrsji"/><path clip-rule="evenodd" class="fn6lbqmuk"/><path class="afy8xbjmk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:street-view-bold" {...props}></Icon>
