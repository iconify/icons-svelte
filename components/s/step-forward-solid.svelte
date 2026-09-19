<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j432o5vub.css';
import '../../css/i/i5ssqcpbz.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 j432o5vub"/><rect class="clr-i-solid clr-i-solid-path-2 i5ssqcpbz"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:step-forward-solid" {...props}></Icon>
