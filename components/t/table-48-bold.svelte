<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcfuqov3g.css';
import '../../css/e/en3-o2bvd.css';
import '../../css/i/i2qirabca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gcfuqov3g"/><path class="en3-o2bvd"/><path class="i2qirabca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:table-48-bold" {...props}></Icon>
