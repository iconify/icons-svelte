<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm0r1bb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nm0r1bb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tarot-15-the-devil" {...props}></Icon>
