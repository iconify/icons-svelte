<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw3b_777n.css';
import '../../css/s/s6mui_bce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bw3b_777n"/><path class="s6mui_bce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:trip-pin-multiple-bold" {...props}></Icon>
