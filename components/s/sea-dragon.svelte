<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqgpx8bfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pqgpx8bfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sea-dragon" {...props}></Icon>
