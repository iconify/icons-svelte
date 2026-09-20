<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qijexu2va.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qijexu2va"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:volume-1" {...props}></Icon>
