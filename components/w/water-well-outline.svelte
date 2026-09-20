<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2h65pwta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2h65pwta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:water-well-outline" {...props}></Icon>
