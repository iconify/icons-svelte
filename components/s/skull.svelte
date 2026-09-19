<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci7k0p4bs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ci7k0p4bs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:skull" {...props}></Icon>
