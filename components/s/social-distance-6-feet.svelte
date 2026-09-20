<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrvc4db4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrvc4db4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:social-distance-6-feet" {...props}></Icon>
