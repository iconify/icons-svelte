<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3k-9lb1z.css';
import '../../css/u/u79pk-b6p.css';
import '../../css/e/exgpfybkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3k-9lb1z"/><path class="u79pk-b6p"/><path class="exgpfybkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:video-file-download-bold" {...props}></Icon>
