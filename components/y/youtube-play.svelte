<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd7ebx84s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pd7ebx84s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:youtube-play" {...props}></Icon>
