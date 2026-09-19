<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9-lfie1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="m9-lfie1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:ruler-combined-bold" {...props}></Icon>
