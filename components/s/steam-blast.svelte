<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqo2l2bps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kqo2l2bps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:steam-blast" {...props}></Icon>
