<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctf2s_bgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ctf2s_bgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:video-player" {...props}></Icon>
