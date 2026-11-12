<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0e7f5gtl.css';
import '../../css/w/wzq2d5gcq.css';
import '../../css/y/ygjyfvpzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j0e7f5gtl"/><path class="wzq2d5gcq"/><path class="ygjyfvpzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:steamgriddb-light" {...props}></Icon>
