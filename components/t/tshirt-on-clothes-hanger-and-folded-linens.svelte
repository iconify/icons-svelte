<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw2c6mblg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gw2c6mblg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tshirt-on-clothes-hanger-and-folded-linens" {...props}></Icon>
