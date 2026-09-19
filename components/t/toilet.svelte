<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yy0lwfb_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="yy0lwfb_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:toilet" {...props}></Icon>
