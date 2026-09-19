<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g06g2je2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="g06g2je2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:z-duo" {...props}></Icon>
