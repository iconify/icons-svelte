<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykan6rbxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ykan6rbxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ticc-dash-dark" {...props}></Icon>
