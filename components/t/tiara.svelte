<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra116g8gq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ra116g8gq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tiara" {...props}></Icon>
