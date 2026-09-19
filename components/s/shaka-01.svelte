<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyqja-u_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xyqja-u_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:shaka-01" {...props}></Icon>
