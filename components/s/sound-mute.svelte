<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/louj8cble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="louj8cble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:sound-mute" {...props}></Icon>
