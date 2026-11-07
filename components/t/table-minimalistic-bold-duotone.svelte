<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nayqy1c_r.css';
import '../../css/k/kydc5glkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nayqy1c_r"/><path class="kydc5glkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:table-minimalistic-bold-duotone" {...props}></Icon>
