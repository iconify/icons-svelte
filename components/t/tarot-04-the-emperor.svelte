<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aesifltmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aesifltmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tarot-04-the-emperor" {...props}></Icon>
