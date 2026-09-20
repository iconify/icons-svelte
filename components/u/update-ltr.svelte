<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smhd_bzjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="smhd_bzjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:update-ltr" {...props}></Icon>
