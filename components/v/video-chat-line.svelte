<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s69omnchh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s69omnchh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:video-chat-line" {...props}></Icon>
