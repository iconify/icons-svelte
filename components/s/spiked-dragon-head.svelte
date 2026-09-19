<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmk8_o-us.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rmk8_o-us"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spiked-dragon-head" {...props}></Icon>
