<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp96po1hv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dp96po1hv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:timeline-alert-outline" {...props}></Icon>
