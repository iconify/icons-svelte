<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etyhwsmin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="etyhwsmin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:snail-eyes" {...props}></Icon>
