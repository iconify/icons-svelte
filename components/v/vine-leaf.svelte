<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7st3j_tx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l7st3j_tx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:vine-leaf" {...props}></Icon>
