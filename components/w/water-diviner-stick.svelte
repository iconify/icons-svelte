<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps9drxb_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ps9drxb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:water-diviner-stick" {...props}></Icon>
