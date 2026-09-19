<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5ged9b_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="m5ged9b_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:seek-skip" {...props}></Icon>
