<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpcec9boj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rpcec9boj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tree-beehive" {...props}></Icon>
