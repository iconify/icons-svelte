<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqev_jbtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jqev_jbtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:star-cycle" {...props}></Icon>
