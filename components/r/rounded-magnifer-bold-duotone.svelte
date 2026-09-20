<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcpnkmxdp.css';
import '../../css/t/t4z7qo_ir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kcpnkmxdp"/><path clip-rule="evenodd" class="t4z7qo_ir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rounded-magnifer-bold-duotone" {...props}></Icon>
