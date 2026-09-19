<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyawn68za.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="wyawn68za"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:shovel" {...props}></Icon>
