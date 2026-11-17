<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw8xpnbmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rw8xpnbmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:square-axis-vertical" {...props}></Icon>
