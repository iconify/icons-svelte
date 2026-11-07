<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0tkg9bgp.css';
import '../../css/p/pbv_9xbam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z0tkg9bgp"/><path class="pbv_9xbam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-arrow-right-up-bold-duotone" {...props}></Icon>
