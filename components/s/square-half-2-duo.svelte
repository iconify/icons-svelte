<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/j7cqu14cb.css';
import '../../css/c/czgf4idyq.css';
import '../../css/n/nqw0fzb0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="j7cqu14cb"/><path class="czgf4idyq"/><path class="nqw0fzb0z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:square-half-2-duo" {...props}></Icon>
