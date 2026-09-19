<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgs-q4b7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="zgs-q4b7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:square-plus" {...props}></Icon>
