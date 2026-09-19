<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcamlfw4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pcamlfw4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:soul-vessel" {...props}></Icon>
