<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a577o8l2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a577o8l2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:swap-bag" {...props}></Icon>
