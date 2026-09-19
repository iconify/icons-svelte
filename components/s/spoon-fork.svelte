<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyph80boj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eyph80boj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:spoon-fork" {...props}></Icon>
