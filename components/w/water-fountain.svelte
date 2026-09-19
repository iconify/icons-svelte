<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsrtltcif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fsrtltcif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:water-fountain" {...props}></Icon>
