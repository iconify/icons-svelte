<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3ok7lntz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d3ok7lntz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tooltip-text-outline" {...props}></Icon>
