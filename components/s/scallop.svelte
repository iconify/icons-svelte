<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7lu1v5bf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u7lu1v5bf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:scallop" {...props}></Icon>
