<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hl3p7dbdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hl3p7dbdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:swordwoman" {...props}></Icon>
