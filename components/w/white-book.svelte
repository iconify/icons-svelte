<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0c-0xbuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n0c-0xbuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:white-book" {...props}></Icon>
