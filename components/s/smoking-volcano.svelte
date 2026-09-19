<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f11ni23_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f11ni23_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:smoking-volcano" {...props}></Icon>
