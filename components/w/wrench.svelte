<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fff0u4ydj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fff0u4ydj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:wrench" {...props}></Icon>
