<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4hn48fcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4hn48fcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:telegram-line" {...props}></Icon>
