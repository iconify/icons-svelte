<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbta3-b_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="hbta3-b_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:two-arrow-in-left-right" {...props}></Icon>
