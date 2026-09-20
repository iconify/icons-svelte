<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu5_ctb_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qu5_ctb_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:upload-cloud-2-line" {...props}></Icon>
