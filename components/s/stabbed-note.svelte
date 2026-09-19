<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzdz8f2mo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mzdz8f2mo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:stabbed-note" {...props}></Icon>
