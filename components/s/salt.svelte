<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7vnfusos.css';
import '../../css/i/ia1foupjh.css';
import '../../css/a/ag43tybwg.css';
import '../../css/a/azx8l-8-x.css';
import '../../css/x/xjsvhebnt.css';
import '../../css/b/bf5ccccov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="r7vnfusos"/><path class="ia1foupjh"/><path class="ag43tybwg"/><circle class="azx8l-8-x"/><circle class="xjsvhebnt"/><circle class="bf5ccccov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:salt" {...props}></Icon>
