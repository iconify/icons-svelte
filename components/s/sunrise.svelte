<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru_76vphk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ru_76vphk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sunrise" {...props}></Icon>
