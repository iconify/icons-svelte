<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnmlbv_ah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cnmlbv_ah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tigera-dark" {...props}></Icon>
