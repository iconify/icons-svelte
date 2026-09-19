<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppmjynbai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ppmjynbai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:x-duo" {...props}></Icon>
