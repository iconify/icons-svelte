<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dns_7678t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dns_7678t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:timeline-clock" {...props}></Icon>
