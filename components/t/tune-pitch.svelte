<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tava8bboo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tava8bboo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tune-pitch" {...props}></Icon>
