<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/is9u0rkgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="is9u0rkgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:t-rex-skull" {...props}></Icon>
