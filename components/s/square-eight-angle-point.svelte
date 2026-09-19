<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4fiu1brv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="x4fiu1brv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:square-eight-angle-point" {...props}></Icon>
