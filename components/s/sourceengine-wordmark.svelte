<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gax-3p3_e.css';
import '../../css/c/cz41hf7gw.css';
import '../../css/d/ds0r57bdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="gax-3p3_e"/><path class="cz41hf7gw"/><path class="ds0r57bdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:sourceengine-wordmark" {...props}></Icon>
