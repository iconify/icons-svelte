<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/diklabb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="diklabb7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:video-movies-play" {...props}></Icon>
