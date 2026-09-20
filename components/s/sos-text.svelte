<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unsv5v4cm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="unsv5v4cm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:sos-text" {...props}></Icon>
