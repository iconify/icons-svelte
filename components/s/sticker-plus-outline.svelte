<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fltzu3bly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fltzu3bly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sticker-plus-outline" {...props}></Icon>
