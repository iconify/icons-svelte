<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo9rxccoo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="yo9rxccoo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:wind-beaufort-5" {...props}></Icon>
