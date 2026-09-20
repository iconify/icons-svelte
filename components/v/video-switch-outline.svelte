<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxmr4jb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxmr4jb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:video-switch-outline" {...props}></Icon>
