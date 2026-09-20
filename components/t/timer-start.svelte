<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzq7v3b7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzq7v3b7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:timer-start" {...props}></Icon>
