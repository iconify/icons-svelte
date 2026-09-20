<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghp9c2bgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghp9c2bgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:water-boiler-off" {...props}></Icon>
