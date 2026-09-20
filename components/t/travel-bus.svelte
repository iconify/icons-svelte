<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikzuh16qp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ikzuh16qp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:travel-bus" {...props}></Icon>
