<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8a2d4biq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q8a2d4biq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tarot-07-the-chariot" {...props}></Icon>
