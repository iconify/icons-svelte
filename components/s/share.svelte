<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3lbt79lb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w3lbt79lb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:share" {...props}></Icon>
