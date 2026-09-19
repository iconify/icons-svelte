<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwd4xibku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wwd4xibku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:william-tell" {...props}></Icon>
