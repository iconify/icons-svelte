<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkza26tve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="vkza26tve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:satellite-dish-fill" {...props}></Icon>
