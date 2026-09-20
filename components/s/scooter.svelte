<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo6upge-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jo6upge-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:scooter" {...props}></Icon>
