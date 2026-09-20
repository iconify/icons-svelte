<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whp7a6bap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="whp7a6bap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tipi-campsite-with-shekel" {...props}></Icon>
