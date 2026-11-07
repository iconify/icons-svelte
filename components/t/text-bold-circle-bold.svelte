<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_o_lwkuc.css';
import '../../css/x/xjaw9ykwq.css';
import '../../css/x/xri1c9bdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_o_lwkuc"/><path class="xjaw9ykwq"/><path clip-rule="evenodd" class="xri1c9bdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-bold-circle-bold" {...props}></Icon>
