<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4-_vlatj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p4-_vlatj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:verilog" {...props}></Icon>
