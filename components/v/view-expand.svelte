<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd6dph84t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="vd6dph84t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:view-expand" {...props}></Icon>
