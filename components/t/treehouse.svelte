<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp8_upbeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cp8_upbeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:treehouse" {...props}></Icon>
