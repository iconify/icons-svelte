<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2s38yz9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="x2s38yz9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:six" {...props}></Icon>
