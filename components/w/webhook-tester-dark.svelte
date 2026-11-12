<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rllixy2pz.css';
import '../../css/d/d7qghsrap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rllixy2pz"/><path class="d7qghsrap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:webhook-tester-dark" {...props}></Icon>
