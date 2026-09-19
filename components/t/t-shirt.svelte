<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/a/a1d9gzssy.css';
import '../../css/w/wthtsqq1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<g class="n1lsf0bnc"><path class="a1d9gzssy"/><path class="wthtsqq1n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:t-shirt" {...props}></Icon>
