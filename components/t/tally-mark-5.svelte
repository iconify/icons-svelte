<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a926f0bag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a926f0bag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tally-mark-5" {...props}></Icon>
