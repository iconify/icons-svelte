<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8z7jfbhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i8z7jfbhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:text-align-left" {...props}></Icon>
