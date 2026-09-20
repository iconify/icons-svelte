<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dc5q0zoak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dc5q0zoak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:trophy-broken" {...props}></Icon>
