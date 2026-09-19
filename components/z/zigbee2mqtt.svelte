<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq8waybzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cq8waybzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:zigbee2mqtt" {...props}></Icon>
