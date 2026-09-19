<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxy_h0r5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":384};
const content = `<path class="rxy_h0r5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:tag" {...props}></Icon>
