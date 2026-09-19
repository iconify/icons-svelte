<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqt3yscwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="aqt3yscwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:trumpet" {...props}></Icon>
