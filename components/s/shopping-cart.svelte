<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gc06xoozo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="gc06xoozo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:shopping-cart" {...props}></Icon>
