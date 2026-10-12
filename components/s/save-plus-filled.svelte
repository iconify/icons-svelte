<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yismpnbbv.css';
import '../../css/i/i2hk_6_pb.css';
import '../../css/i/iex7obabp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yismpnbbv"/><path class="i2hk_6_pb"/><path class="iex7obabp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:save-plus-filled" {...props}></Icon>
