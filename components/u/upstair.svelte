<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku6mcablf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="ku6mcablf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:upstair" {...props}></Icon>
