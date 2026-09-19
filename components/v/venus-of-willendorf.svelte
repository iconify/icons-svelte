<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd86mdi0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pd86mdi0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:venus-of-willendorf" {...props}></Icon>
