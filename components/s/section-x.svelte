<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mn2f94bfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mn2f94bfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:section-x" {...props}></Icon>
