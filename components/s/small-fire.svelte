<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af8sc-fzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="af8sc-fzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:small-fire" {...props}></Icon>
