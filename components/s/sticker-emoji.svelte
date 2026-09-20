<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr3967dct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wr3967dct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sticker-emoji" {...props}></Icon>
