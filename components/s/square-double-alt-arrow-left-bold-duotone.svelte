<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg928d-qd.css';
import '../../css/a/a8qzt_a5q.css';
import '../../css/d/dkxc4fbsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vg928d-qd"/><path class="a8qzt_a5q"/><path class="dkxc4fbsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-double-alt-arrow-left-bold-duotone" {...props}></Icon>
