<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z66tl_b8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z66tl_b8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:toad-teeth" {...props}></Icon>
