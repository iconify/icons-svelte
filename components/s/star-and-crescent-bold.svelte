<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/irjh9jilq.css';
import '../../css/g/ggd2cgbpw.css';
import '../../css/y/yyrmujbrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="irjh9jilq"/><path class="ggd2cgbpw"/><path class="yyrmujbrk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:star-and-crescent-bold" {...props}></Icon>
