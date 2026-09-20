<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcl5iabln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcl5iabln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:volume-3" {...props}></Icon>
