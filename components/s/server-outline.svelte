<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kycx_culd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kycx_culd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:server-outline" {...props}></Icon>
