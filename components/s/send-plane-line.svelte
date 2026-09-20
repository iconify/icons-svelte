<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s97pvnh2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s97pvnh2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:send-plane-line" {...props}></Icon>
