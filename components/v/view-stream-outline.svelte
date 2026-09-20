<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwa6k3roj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwa6k3roj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:view-stream-outline" {...props}></Icon>
