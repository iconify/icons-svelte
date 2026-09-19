<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4tn3wbcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p4tn3wbcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:vanilla-flower" {...props}></Icon>
