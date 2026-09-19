<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rou9muzmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="rou9muzmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:shopping-cart-sign" {...props}></Icon>
