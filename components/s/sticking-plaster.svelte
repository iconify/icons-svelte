<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lftjc7k9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lftjc7k9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sticking-plaster" {...props}></Icon>
