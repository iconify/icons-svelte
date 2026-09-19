<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_xovd5yc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_xovd5yc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:video-off" {...props}></Icon>
