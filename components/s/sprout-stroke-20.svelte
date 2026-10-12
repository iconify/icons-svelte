<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co_xwekit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="co_xwekit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:sprout-stroke-20" {...props}></Icon>
