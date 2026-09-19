<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfgh54_oh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pfgh54_oh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:skills" {...props}></Icon>
