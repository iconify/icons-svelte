<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-tx9_o5y.css';
import '../../css/l/l3l94kbvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h-tx9_o5y"/><path class="l3l94kbvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:upload-16" {...props}></Icon>
