<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg7dov6vb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vg7dov6vb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:turkey-leg-off" {...props}></Icon>
