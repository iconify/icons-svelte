<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stkdhzbtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="stkdhzbtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:surround-sound-5-1-2" {...props}></Icon>
