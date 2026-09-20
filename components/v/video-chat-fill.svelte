<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5hfnwz9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5hfnwz9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:video-chat-fill" {...props}></Icon>
