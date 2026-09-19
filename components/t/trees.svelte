<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a03eb3b2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="a03eb3b2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:trees" {...props}></Icon>
