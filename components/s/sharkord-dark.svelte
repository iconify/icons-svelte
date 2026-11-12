<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl117jbyi.css';
import '../../css/i/ipbgiccho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tl117jbyi"/><path class="ipbgiccho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sharkord-dark" {...props}></Icon>
