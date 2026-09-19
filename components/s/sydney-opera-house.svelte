<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfqbepblz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mfqbepblz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sydney-opera-house" {...props}></Icon>
