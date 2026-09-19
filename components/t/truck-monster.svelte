<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p90omnbqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="p90omnbqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:truck-monster" {...props}></Icon>
