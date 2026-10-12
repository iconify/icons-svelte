<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5-qb4ycp.css';
import '../../css/l/l4r5fel4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r5-qb4ycp"/><path class="l4r5fel4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:webcam-off-filled" {...props}></Icon>
