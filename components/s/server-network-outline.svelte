<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdh0wop_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tdh0wop_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:server-network-outline" {...props}></Icon>
