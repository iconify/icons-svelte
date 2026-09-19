<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylkgm9bed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ylkgm9bed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:take-my-money" {...props}></Icon>
