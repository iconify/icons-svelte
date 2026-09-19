<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwm7y7b8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dwm7y7b8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sea-star" {...props}></Icon>
