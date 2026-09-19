<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo-n8x3at.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jo-n8x3at"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:stone-pile" {...props}></Icon>
