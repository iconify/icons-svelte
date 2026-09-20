<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctjzpmbpg.css';
import '../../css/r/ry3qkjbjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ctjzpmbpg"/><path class="ry3qkjbjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sshwifty-dark" {...props}></Icon>
