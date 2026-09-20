<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru3w11duv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ru3w11duv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:search-ai-4-line" {...props}></Icon>
