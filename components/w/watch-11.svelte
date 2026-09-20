<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjo077brx.css';
import '../../css/x/x4_qz_bvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="qjo077brx"/><path class="x4_qz_bvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:watch-11" {...props}></Icon>
