<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl7hvkm3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="vl7hvkm3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:underline" {...props}></Icon>
