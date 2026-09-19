<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpnwm6bbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gpnwm6bbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:toggles" {...props}></Icon>
