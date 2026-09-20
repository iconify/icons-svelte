<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tye0q80jh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tye0q80jh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:timeline-minus-outline" {...props}></Icon>
