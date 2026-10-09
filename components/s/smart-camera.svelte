<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4h8u2bgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4h8u2bgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:smart-camera" {...props}></Icon>
