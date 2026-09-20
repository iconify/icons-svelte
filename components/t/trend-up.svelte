<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-j-vqbls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="f-j-vqbls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:trend-up" {...props}></Icon>
