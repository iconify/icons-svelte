<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxdneib_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pxdneib_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shield-off-fill-round" {...props}></Icon>
