<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/laa_ont7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="laa_ont7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sliced-mushroom" {...props}></Icon>
