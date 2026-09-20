<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sob9rmb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sob9rmb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:triangle-minus-2" {...props}></Icon>
