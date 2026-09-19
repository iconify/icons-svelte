<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kurhgmb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kurhgmb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:steam-locomotive" {...props}></Icon>
