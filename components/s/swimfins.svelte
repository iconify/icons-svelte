<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjkb6mbzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pjkb6mbzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:swimfins" {...props}></Icon>
