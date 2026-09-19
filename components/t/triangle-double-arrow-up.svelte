<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/v/v1dlfbb5m.css';
import '../../css/i/iy7wambnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":17};
const content = `<g class="n1lsf0bnc"><path class="v1dlfbb5m"/><path class="iy7wambnn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:triangle-double-arrow-up" {...props}></Icon>
