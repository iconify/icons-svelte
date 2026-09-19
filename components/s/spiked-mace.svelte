<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hla5x_bzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hla5x_bzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spiked-mace" {...props}></Icon>
