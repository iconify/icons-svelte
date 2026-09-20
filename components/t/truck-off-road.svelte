<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4e7c1v5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4e7c1v5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:truck-off-road" {...props}></Icon>
