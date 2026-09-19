<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw5dt7bmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vw5dt7bmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sunglasses" {...props}></Icon>
