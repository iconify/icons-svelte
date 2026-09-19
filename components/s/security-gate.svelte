<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1-vgb93d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v1-vgb93d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:security-gate" {...props}></Icon>
