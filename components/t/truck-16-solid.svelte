<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhsrn1yyz.css';
import '../../css/j/jro2vlvum.css';
import '../../css/y/y0id5tbpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yhsrn1yyz"/><path class="jro2vlvum"/><path class="y0id5tbpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:truck-16-solid" {...props}></Icon>
