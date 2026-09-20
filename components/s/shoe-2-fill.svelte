<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l61g_dw_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l61g_dw_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shoe-2-fill" {...props}></Icon>
