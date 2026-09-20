<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcduwehnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wcduwehnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:triangle-up-with-plus" {...props}></Icon>
