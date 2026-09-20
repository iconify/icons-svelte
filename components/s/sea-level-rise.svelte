<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u99l2yxgv.css';
import '../../css/z/z04drlb1l.css';
import '../../css/i/i650vrpib.css';
import '../../css/e/e0rq2fx8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="u99l2yxgv"/><g class="z04drlb1l"><path class="i650vrpib"/><path class="e0rq2fx8z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:sea-level-rise" {...props}></Icon>
