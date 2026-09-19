<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy5y2-b2m.css';
import '../../css/f/f-4zf_bip.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 cy5y2-b2m"/><path class="clr-i-outline clr-i-outline-path-2 f-4zf_bip"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:step-forward-2-line" {...props}></Icon>
