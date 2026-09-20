<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4v_z4_rj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o4v_z4_rj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:speed-up-line" {...props}></Icon>
