<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmfocq2ph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="tmfocq2ph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:square-dashed-2" {...props}></Icon>
