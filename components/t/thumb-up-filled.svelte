<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvhheqbjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uvhheqbjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:thumb-up-filled" {...props}></Icon>
