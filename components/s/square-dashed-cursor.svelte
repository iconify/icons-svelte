<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk-a-0bdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rk-a-0bdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:square-dashed-cursor" {...props}></Icon>
