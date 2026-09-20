<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnaelyb2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qnaelyb2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:shell-window-minimize-filled" {...props}></Icon>
