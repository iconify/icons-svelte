<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvfxynb0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1408,"height":1536};
const content = `<path class="vvfxynb0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:trash" {...props}></Icon>
