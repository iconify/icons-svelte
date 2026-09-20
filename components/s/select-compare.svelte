<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn_8x9o0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rn_8x9o0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:select-compare" {...props}></Icon>
