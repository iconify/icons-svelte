<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6f0j9bmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x6f0j9bmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:temps-light" {...props}></Icon>
