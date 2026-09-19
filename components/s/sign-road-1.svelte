<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyr8vnyio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="vyr8vnyio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:sign-road-1" {...props}></Icon>
