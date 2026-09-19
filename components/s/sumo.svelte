<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp9hfacyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lp9hfacyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:sumo" {...props}></Icon>
