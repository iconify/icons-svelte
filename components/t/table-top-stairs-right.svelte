<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2804ochd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="m2804ochd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:table-top-stairs-right" {...props}></Icon>
