<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc_k_y0gh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jc_k_y0gh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:virus-x" {...props}></Icon>
