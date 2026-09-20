<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_k0u_bip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="h_k0u_bip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:sandbox-with-sand-trowel" {...props}></Icon>
