<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrax_sb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="rrax_sb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:shift-right" {...props}></Icon>
