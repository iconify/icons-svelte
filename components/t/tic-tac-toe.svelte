<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hww2_jbko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hww2_jbko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tic-tac-toe" {...props}></Icon>
