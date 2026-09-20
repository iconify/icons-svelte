<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4bm74j-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x4bm74j-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:video-movies-video-square" {...props}></Icon>
