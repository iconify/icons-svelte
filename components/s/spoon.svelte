<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0ku_mbre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m0ku_mbre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spoon" {...props}></Icon>
