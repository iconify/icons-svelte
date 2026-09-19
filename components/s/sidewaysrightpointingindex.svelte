<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl161n-1i.css';
import '../../css/f/fgm3acnse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cl161n-1i"/><path class="fgm3acnse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:sidewaysrightpointingindex" {...props}></Icon>
