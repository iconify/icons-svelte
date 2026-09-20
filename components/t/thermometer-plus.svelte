<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m67r0olii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m67r0olii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:thermometer-plus" {...props}></Icon>
