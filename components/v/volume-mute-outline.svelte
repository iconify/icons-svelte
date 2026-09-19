<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbi1n57ce.css';
import '../../css/m/mc8nkccec.css';
import '../../css/m/m286a39yt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bbi1n57ce"/><path class="mc8nkccec"/><path class="m286a39yt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:volume-mute-outline" {...props}></Icon>
