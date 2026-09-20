<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0_q8-y1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u0_q8-y1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:split-vertically" {...props}></Icon>
