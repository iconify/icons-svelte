<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu0vypbpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cu0vypbpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:vote" {...props}></Icon>
