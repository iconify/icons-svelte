<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/q/qh1hhtown.css';
import '../../css/s/san_b9rep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="n1lsf0bnc"><path class="qh1hhtown"/><path class="san_b9rep"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:triangle-double-arrow-right" {...props}></Icon>
