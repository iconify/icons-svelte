<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it9cnwzdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="it9cnwzdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:satellite" {...props}></Icon>
