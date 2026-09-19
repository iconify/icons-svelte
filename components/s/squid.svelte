<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad4jeu_wy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ad4jeu_wy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:squid" {...props}></Icon>
