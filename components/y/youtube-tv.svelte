<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl4nvpb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yl4nvpb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:youtube-tv" {...props}></Icon>
