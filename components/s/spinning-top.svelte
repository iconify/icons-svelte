<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ts5h3obps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ts5h3obps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spinning-top" {...props}></Icon>
