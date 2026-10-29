<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4bp63bqf.css';
import '../../css/u/upne6j1lj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-a x4bp63bqf"/><path class="upne6j1lj wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:sun" {...props}></Icon>
