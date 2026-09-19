<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg45s4b0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fg45s4b0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:top-paw" {...props}></Icon>
