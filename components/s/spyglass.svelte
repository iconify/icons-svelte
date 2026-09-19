<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk8uohblm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mk8uohblm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spyglass" {...props}></Icon>
