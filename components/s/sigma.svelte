<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3dv8bc_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r3dv8bc_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:sigma" {...props}></Icon>
