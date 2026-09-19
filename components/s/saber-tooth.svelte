<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwjqv_u-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hwjqv_u-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:saber-tooth" {...props}></Icon>
