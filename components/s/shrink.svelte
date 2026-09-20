<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg47dm5zr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="rg47dm5zr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:shrink" {...props}></Icon>
