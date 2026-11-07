<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nayqy1c_r.css';
import '../../css/n/nrrsncbey.css';
import '../../css/n/nh6q7vamn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nayqy1c_r"/><path class="nrrsncbey"/><path class="nh6q7vamn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:table-cells-merge-bold-duotone" {...props}></Icon>
