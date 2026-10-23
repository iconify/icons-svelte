<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npko2sbgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="npko2sbgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:square-dashed-x" {...props}></Icon>
