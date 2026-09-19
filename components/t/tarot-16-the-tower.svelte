<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/viapxsbol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="viapxsbol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tarot-16-the-tower" {...props}></Icon>
