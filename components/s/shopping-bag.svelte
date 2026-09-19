<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwnn6yb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iwnn6yb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:shopping-bag" {...props}></Icon>
