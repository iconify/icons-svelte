<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trf3a5mss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="trf3a5mss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:select" {...props}></Icon>
