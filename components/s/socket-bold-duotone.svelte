<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn_frcb-c.css';
import '../../css/n/n9_kl16fx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jn_frcb-c"/><path clip-rule="evenodd" class="n9_kl16fx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:socket-bold-duotone" {...props}></Icon>
