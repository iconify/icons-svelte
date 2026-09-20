<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-3_x9pzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m-3_x9pzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:suggestarr-light" {...props}></Icon>
