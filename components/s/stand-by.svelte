<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkv-isb8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zkv-isb8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:stand-by" {...props}></Icon>
