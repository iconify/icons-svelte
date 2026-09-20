<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvftp6bcy.css';
import '../../css/i/i3i0qbcpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvftp6bcy"/><path class="i3i0qbcpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:zano" {...props}></Icon>
