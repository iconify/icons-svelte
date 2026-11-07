<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl89sibfb.css';
import '../../css/n/nayqy1c_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yl89sibfb"/><path class="nayqy1c_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rows-2-bold-duotone" {...props}></Icon>
