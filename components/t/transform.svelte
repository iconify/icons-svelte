<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz2b7dbmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":480};
const content = `<path class="jz2b7dbmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:transform" {...props}></Icon>
