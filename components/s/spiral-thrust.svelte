<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mooid3-qp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mooid3-qp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spiral-thrust" {...props}></Icon>
