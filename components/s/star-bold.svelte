<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvd_l_cdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="rvd_l_cdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:star-bold" {...props}></Icon>
