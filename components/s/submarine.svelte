<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl_vy435b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bl_vy435b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:submarine" {...props}></Icon>
