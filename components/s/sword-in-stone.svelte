<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcsogpb0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dcsogpb0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sword-in-stone" {...props}></Icon>
