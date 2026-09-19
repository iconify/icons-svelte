<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzwv2ebuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="dzwv2ebuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:shopping-basket" {...props}></Icon>
