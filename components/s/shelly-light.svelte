<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv13l7o3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vv13l7o3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:shelly-light" {...props}></Icon>
