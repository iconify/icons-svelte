<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue1ltq7mh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ue1ltq7mh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:v" {...props}></Icon>
