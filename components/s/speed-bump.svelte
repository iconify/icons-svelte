<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qffx2xbcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qffx2xbcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:speed-bump" {...props}></Icon>
