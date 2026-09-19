<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfxxj0z4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="rfxxj0z4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:share-square" {...props}></Icon>
