<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7nmgfboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m7nmgfboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:striking-clamps" {...props}></Icon>
