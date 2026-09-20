<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhi976k0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhi976k0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:tiktok" {...props}></Icon>
