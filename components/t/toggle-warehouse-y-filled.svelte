<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrhf_hbwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wrhf_hbwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:toggle-warehouse-y-filled" {...props}></Icon>
