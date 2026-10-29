<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu6-mip-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qu6-mip-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:wrench" {...props}></Icon>
