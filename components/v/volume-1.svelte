<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzfet62zx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="vzfet62zx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:volume-1" {...props}></Icon>
