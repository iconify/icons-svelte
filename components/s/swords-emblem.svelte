<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-ef07b7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i-ef07b7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:swords-emblem" {...props}></Icon>
