<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhe6x9bga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nhe6x9bga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:target-prize" {...props}></Icon>
