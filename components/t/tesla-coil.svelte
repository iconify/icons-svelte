<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-lvy5bqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u-lvy5bqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tesla-coil" {...props}></Icon>
