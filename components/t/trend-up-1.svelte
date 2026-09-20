<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahn2rbxwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahn2rbxwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:trend-up-1" {...props}></Icon>
