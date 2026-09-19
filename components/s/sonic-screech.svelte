<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kimpx1j4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kimpx1j4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sonic-screech" {...props}></Icon>
