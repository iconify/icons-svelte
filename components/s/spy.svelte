<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub56r4xjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ub56r4xjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spy" {...props}></Icon>
