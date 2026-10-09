<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9nf_fbqv.css';
import '../../css/r/rn7_tzbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f9nf_fbqv"/><path class="rn7_tzbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:water-bottle-20-bold" {...props}></Icon>
