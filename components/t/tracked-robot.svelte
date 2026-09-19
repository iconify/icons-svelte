<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3wig2b0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c3wig2b0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tracked-robot" {...props}></Icon>
