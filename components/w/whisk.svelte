<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfz43q1cs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tfz43q1cs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:whisk" {...props}></Icon>
