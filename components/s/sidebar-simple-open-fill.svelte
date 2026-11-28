<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx_bfl8jf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="lx_bfl8jf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:sidebar-simple-open-fill" {...props}></Icon>
