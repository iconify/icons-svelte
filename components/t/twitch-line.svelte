<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uft_mybdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uft_mybdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:twitch-line" {...props}></Icon>
