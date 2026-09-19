<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhp6d1bjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fhp6d1bjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spooky-house" {...props}></Icon>
