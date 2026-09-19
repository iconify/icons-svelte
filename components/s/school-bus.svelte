<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_f_gsbag.css';
import '../../css/v/v22w14b1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_f_gsbag"/><path class="v22w14b1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:school-bus" {...props}></Icon>
