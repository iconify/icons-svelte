<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq9u-lbic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lq9u-lbic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tightrope" {...props}></Icon>
