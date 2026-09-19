<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vj2ys662g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":384};
const content = `<path class="vj2ys662g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:wb-auto" {...props}></Icon>
