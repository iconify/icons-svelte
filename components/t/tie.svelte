<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw7xa2b-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lw7xa2b-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tie" {...props}></Icon>
