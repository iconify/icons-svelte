<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5rcylbor.css';
import '../../css/f/f5v57gbdv.css';
import '../../css/e/erjzr4f8q.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 l5rcylbor"/><path class="clr-i-outline clr-i-outline-path-2 f5v57gbdv"/><path class="clr-i-outline clr-i-outline-path-3 erjzr4f8q"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:target-line" {...props}></Icon>
