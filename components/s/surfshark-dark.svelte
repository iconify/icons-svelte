<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_hx8ibfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d_hx8ibfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:surfshark-dark" {...props}></Icon>
