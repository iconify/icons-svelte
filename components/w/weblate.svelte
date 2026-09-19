<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq44mglgu.css';
import '../../css/s/sobdcvb0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="cq44mglgu weblate-plain-st0"/><path class="sobdcvb0f weblate-plain-st0"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:weblate" {...props}></Icon>
