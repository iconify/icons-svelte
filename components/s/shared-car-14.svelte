<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm08promo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="zm08promo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:shared-car-14" {...props}></Icon>
