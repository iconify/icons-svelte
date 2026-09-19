<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy0omibrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sy0omibrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:skull-shield" {...props}></Icon>
