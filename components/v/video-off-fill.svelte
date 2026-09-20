<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmgaybccy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmgaybccy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:video-off-fill" {...props}></Icon>
