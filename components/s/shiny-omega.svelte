<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y538k-qat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y538k-qat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:shiny-omega" {...props}></Icon>
