<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg5c0-v8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vg5c0-v8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:train-car-centerbeam-full" {...props}></Icon>
