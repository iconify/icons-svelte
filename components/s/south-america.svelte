<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-gw35bmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k-gw35bmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:south-america" {...props}></Icon>
