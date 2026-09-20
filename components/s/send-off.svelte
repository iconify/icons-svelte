<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlx0s_w4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dlx0s_w4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:send-off" {...props}></Icon>
