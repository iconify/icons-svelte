<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmo3-snvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rmo3-snvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:skull-in-jar" {...props}></Icon>
