<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x50dklg_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x50dklg_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:vip-outline" {...props}></Icon>
