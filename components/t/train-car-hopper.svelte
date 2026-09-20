<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/im7t84bbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="im7t84bbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:train-car-hopper" {...props}></Icon>
