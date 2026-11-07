<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6hevcvfn.css';
import '../../css/t/t3y9293jz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u6hevcvfn"/><path clip-rule="evenodd" class="t3y9293jz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shield-network-bold-duotone" {...props}></Icon>
