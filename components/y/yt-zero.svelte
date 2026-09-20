<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh1f6ibkg.css';
import '../../css/a/ax8lognen.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yh1f6ibkg"/><path class="ax8lognen"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yt-zero" {...props}></Icon>
