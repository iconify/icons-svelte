<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7utr94ws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r7utr94ws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:shield-off" {...props}></Icon>
