<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elbx3d_mc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="elbx3d_mc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:tab-close" {...props}></Icon>
