<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vls5gbfof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vls5gbfof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:slider" {...props}></Icon>
