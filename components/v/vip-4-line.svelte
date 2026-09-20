<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjx98-60m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjx98-60m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:vip-4-line" {...props}></Icon>
