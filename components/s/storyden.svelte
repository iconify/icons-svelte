<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo8uvhurx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xo8uvhurx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:storyden" {...props}></Icon>
