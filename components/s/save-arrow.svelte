<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prqr2wber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="prqr2wber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:save-arrow" {...props}></Icon>
