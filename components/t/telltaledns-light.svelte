<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgpp--bcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vgpp--bcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:telltaledns-light" {...props}></Icon>
