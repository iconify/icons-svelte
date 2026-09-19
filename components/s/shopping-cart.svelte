<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft94xac-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":496};
const content = `<path class="ft94xac-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:shopping-cart" {...props}></Icon>
