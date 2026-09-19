<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fza9v8b0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fza9v8b0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:winged-arrow" {...props}></Icon>
