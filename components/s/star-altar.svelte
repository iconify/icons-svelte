<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vext9xb8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vext9xb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:star-altar" {...props}></Icon>
