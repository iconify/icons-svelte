<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqe5nibdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wqe5nibdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:star-stroke-20" {...props}></Icon>
