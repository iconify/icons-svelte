<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns4zjml5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ns4zjml5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spotted-arrowhead" {...props}></Icon>
