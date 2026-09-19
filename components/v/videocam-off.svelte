<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvlzdyfkb.css';
import '../../css/q/qm_k6gbmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fvlzdyfkb"/><path class="qm_k6gbmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:videocam-off" {...props}></Icon>
