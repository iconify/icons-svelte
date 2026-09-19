<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd415ib1g.css';
import '../../css/h/hl-46jmiu.css';
import '../../css/c/cpcuf9xkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="fd415ib1g"/><path class="hl-46jmiu"/><path class="cpcuf9xkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:woocommerce" {...props}></Icon>
