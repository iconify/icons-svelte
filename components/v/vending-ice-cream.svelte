<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg5u6gbbk.css';
import '../../css/b/b3b6v3bli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xg5u6gbbk"/><path class="b3b6v3bli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:vending-ice-cream" {...props}></Icon>
