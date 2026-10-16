<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxyna-beg.css';
import '../../css/g/gr-g1kq_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pxyna-beg"/><path class="gr-g1kq_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tide-low-48" {...props}></Icon>
