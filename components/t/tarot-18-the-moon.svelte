<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imrkppwci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="imrkppwci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tarot-18-the-moon" {...props}></Icon>
