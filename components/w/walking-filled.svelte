<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt_demb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yt_demb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:walking-filled" {...props}></Icon>
