<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am1rs2ilz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="am1rs2ilz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:stereo" {...props}></Icon>
