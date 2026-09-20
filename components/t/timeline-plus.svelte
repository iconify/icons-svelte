<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip6ka8vgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ip6ka8vgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:timeline-plus" {...props}></Icon>
