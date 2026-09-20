<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8mufgdiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l8mufgdiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:washington-with-capital-star" {...props}></Icon>
