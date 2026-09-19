<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0zjmth0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t0zjmth0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:suspension-bridge" {...props}></Icon>
