<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj2od2bbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cj2od2bbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:star-off" {...props}></Icon>
