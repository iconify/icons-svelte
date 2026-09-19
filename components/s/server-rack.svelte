<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8d2fybbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e8d2fybbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:server-rack" {...props}></Icon>
