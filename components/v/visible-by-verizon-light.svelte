<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq7kpbc_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vq7kpbc_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:visible-by-verizon-light" {...props}></Icon>
