<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc_nxd5hd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xc_nxd5hd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:tape-filled" {...props}></Icon>
