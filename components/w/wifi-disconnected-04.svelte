<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6scpwtva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y6scpwtva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:wifi-disconnected-04" {...props}></Icon>
