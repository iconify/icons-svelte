<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5mupbb1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m5mupbb1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spiked-shield" {...props}></Icon>
