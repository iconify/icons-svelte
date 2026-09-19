<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8rkqh9yg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l8rkqh9yg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:well" {...props}></Icon>
