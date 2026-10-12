<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kze1e9b0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kze1e9b0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:text-color-stroke-20" {...props}></Icon>
