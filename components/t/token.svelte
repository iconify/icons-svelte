<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elyw49b3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="elyw49b3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:token" {...props}></Icon>
