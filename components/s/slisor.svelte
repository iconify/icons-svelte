<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fs4ufqbdt.css';
import '../../css/d/dlp7nstpk.css';
import '../../css/t/tzi6_ccop.css';
import '../../css/t/ty36w82wl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fs4ufqbdt"/><circle class="dlp7nstpk"/><path class="tzi6_ccop"/><path class="ty36w82wl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:slisor" {...props}></Icon>
