<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzq5e4blu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mzq5e4blu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:snowman" {...props}></Icon>
