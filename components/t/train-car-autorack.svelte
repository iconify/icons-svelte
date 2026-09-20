<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdazkl9at.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vdazkl9at"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:train-car-autorack" {...props}></Icon>
