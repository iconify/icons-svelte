<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc64tebsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="mc64tebsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:underline" {...props}></Icon>
