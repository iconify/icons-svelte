<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/voz8zc88m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="voz8zc88m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:underline-text-1" {...props}></Icon>
