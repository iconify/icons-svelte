<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es0g2ybga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="es0g2ybga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:umbrella" {...props}></Icon>
