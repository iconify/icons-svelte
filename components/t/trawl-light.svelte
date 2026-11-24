<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4aycwbjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j4aycwbjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:trawl-light" {...props}></Icon>
