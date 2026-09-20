<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_57g2bsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="u_57g2bsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:sword" {...props}></Icon>
