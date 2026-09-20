<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xahzi_p2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xahzi_p2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:video-download-fill" {...props}></Icon>
