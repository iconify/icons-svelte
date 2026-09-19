<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb4nc0b1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hb4nc0b1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:video-camera" {...props}></Icon>
