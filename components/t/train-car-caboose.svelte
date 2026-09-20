<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7b80xumb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j7b80xumb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:train-car-caboose" {...props}></Icon>
