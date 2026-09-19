<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjexg1fid.css';
import '../../css/e/e5jn00b6w.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 xjexg1fid"/><path class="clr-i-solid clr-i-solid-path-2 e5jn00b6w"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:ssd-solid" {...props}></Icon>
