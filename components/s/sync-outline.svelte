<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wic4l3bna.css';
import '../../css/j/j2rwd5epq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wic4l3bna"/><path class="j2rwd5epq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:sync-outline" {...props}></Icon>
