<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_z3i_b0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_z3i_b0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:toggle-on-circle-filled" {...props}></Icon>
