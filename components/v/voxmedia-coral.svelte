<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw_45eb6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fw_45eb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:voxmedia-coral" {...props}></Icon>
