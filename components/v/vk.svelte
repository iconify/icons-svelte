<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmm02yz3c.css';
import '../../css/m/mc6ws4xxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xmm02yz3c"/><path class="mc6ws4xxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:vk" {...props}></Icon>
