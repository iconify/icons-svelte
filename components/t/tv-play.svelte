<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnb_aj5jl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":384};
const content = `<path class="jnb_aj5jl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:tv-play" {...props}></Icon>
