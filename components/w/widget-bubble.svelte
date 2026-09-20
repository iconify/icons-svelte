<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap2_25knx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ap2_25knx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:widget-bubble" {...props}></Icon>
