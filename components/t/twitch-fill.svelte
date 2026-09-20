<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uiv79zbvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uiv79zbvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:twitch-fill" {...props}></Icon>
