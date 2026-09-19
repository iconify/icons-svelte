<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5dpu-bwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="r5dpu-bwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:square" {...props}></Icon>
