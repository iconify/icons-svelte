<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f21xtmb7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="f21xtmb7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:watchtower-14" {...props}></Icon>
