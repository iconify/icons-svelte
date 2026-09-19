<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8sfzpzpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z8sfzpzpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:turbine" {...props}></Icon>
