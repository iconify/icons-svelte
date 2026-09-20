<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-yb3nblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-yb3nblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:store" {...props}></Icon>
