<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz0f1ls1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sz0f1ls1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:swamp-bat" {...props}></Icon>
