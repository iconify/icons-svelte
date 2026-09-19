<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzmae1v_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uzmae1v_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:subscript2" {...props}></Icon>
