<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m93px3bkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m93px3bkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:skull-with-syringe" {...props}></Icon>
