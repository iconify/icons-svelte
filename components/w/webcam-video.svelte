<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkb3oqbwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="jkb3oqbwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:webcam-video" {...props}></Icon>
