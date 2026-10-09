<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0xmcccfl.css';
import '../../css/r/r_8u_eb_k.css';
import '../../css/d/dy97t_1fn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w0xmcccfl"/><path class="r_8u_eb_k"/><path class="dy97t_1fn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:speaker-20-bold" {...props}></Icon>
