<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfi9q604p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rfi9q604p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:travel-car" {...props}></Icon>
