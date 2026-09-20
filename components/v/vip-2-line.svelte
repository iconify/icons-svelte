<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myq_lyb9f.css';
import '../../css/k/kkjzqzj2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="myq_lyb9f"/><path class="kkjzqzj2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:vip-2-line" {...props}></Icon>
