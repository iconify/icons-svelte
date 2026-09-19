<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_p-1bobd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u_p-1bobd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:star-formation" {...props}></Icon>
