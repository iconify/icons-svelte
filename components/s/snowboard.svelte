<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vae13gx0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vae13gx0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:snowboard" {...props}></Icon>
