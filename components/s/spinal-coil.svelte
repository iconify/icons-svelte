<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifk-m6b3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ifk-m6b3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spinal-coil" {...props}></Icon>
