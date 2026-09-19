<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo92d0gtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vo92d0gtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spill" {...props}></Icon>
