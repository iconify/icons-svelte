<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swmzyz2lh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="swmzyz2lh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:wind-flow-2" {...props}></Icon>
