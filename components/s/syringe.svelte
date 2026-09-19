<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuh1g2ctr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vuh1g2ctr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:syringe" {...props}></Icon>
