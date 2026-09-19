<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uiin5c7nl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uiin5c7nl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:saucepan" {...props}></Icon>
