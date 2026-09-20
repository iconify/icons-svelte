<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udq5q0bwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="udq5q0bwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wizarr-light" {...props}></Icon>
