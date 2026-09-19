<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p78hdq_kg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p78hdq_kg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:scout-ship" {...props}></Icon>
