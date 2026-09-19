<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz7yahttz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="gz7yahttz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:two-arrow-left" {...props}></Icon>
