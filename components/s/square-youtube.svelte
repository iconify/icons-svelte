<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq0baacen.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="xq0baacen"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:square-youtube" {...props}></Icon>
