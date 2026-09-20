<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aucf8sb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="aucf8sb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:shell-window-minimize-outline" {...props}></Icon>
