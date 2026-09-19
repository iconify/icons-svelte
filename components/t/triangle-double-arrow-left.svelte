<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/h/hk1s8nqdm.css';
import '../../css/e/ejfxmz1gf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<g class="n1lsf0bnc"><path class="hk1s8nqdm"/><path class="ejfxmz1gf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:triangle-double-arrow-left" {...props}></Icon>
