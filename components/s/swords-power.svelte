<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3x7mfbgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i3x7mfbgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:swords-power" {...props}></Icon>
