<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6k_3kb4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="u6k_3kb4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:shrink-horizontal-1" {...props}></Icon>
