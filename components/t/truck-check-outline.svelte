<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcg6qzbmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fcg6qzbmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:truck-check-outline" {...props}></Icon>
