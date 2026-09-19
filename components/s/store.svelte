<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/teanu_nhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":616,"height":512};
const content = `<path class="teanu_nhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:store" {...props}></Icon>
