<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_kme4g_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x_kme4g_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:unlink-2-fill" {...props}></Icon>
