<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu_dek8wq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xu_dek8wq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:server-network-off" {...props}></Icon>
