<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6a0jkahm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="i6a0jkahm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:site-map-revert" {...props}></Icon>
