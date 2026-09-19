<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia_ti1b7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ia_ti1b7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spikes-half" {...props}></Icon>
