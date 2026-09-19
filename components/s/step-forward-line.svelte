<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8k_ne4ni.css';
import '../../css/j/j9v9tkbrj.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="a8k_ne4ni clr-i-outline clr-i-outline-path-1"/><path class="clr-i-outline clr-i-outline-path-2 j9v9tkbrj"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:step-forward-line" {...props}></Icon>
