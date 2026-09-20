<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nund8c9im.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1534,"height":1536};
const content = `<path class="nund8c9im"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:wind-direction-se" {...props}></Icon>
