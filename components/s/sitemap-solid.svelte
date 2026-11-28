<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cohy3ublc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cohy3ublc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:sitemap-solid" {...props}></Icon>
