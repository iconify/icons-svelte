<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_vsitbjn.css';
import '../../css/c/c_2_mxnve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o_vsitbjn"/><path class="c_2_mxnve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:volume-high" {...props}></Icon>
