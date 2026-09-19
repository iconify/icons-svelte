<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx-z35byx.css';
import '../../css/r/rug5b1b1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="zx-z35byx"/><path class="rug5b1b1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:route-end" {...props}></Icon>
