<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr961sbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wr961sbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:trend-down" {...props}></Icon>
