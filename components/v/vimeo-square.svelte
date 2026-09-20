<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca9mp9bqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ca9mp9bqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:vimeo-square" {...props}></Icon>
