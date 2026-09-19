<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/liy7sib8p.css';
import '../../css/q/qxycx-kwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="liy7sib8p"/><path class="qxycx-kwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:videocam-outline" {...props}></Icon>
