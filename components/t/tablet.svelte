<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2w92b9qn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p2w92b9qn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tablet" {...props}></Icon>
