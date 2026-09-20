<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydldh0bin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ydldh0bin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:voicemail" {...props}></Icon>
