<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbl3c2qzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pbl3c2qzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:shoulder-scales" {...props}></Icon>
