<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dae20rb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dae20rb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:stairs-20-bold" {...props}></Icon>
