<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7wy-vb7x.css';
import '../../css/x/xnp4gerbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i7wy-vb7x"/><path class="xnp4gerbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:trusted-cgi" {...props}></Icon>
