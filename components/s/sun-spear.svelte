<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t03n-gbbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t03n-gbbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sun-spear" {...props}></Icon>
