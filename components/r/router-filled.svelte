<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt5vbccxc.css';
import '../../css/s/s6t1fwbej.css';
import '../../css/f/f57g08bdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tt5vbccxc"/><path class="s6t1fwbej"/><path class="f57g08bdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:router-filled" {...props}></Icon>
