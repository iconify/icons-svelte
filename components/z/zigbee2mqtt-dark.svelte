<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8os171mr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r8os171mr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zigbee2mqtt-dark" {...props}></Icon>
