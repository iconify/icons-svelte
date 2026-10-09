<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvj1k6p0o.css';
import '../../css/h/h5d_4v8si.css';
import '../../css/x/xsz5ie_ke.css';
import '../../css/f/f5h10_v-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zvj1k6p0o"/><path class="h5d_4v8si"/><path class="xsz5ie_ke"/><path class="f5h10_v-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wifi-20-bold" {...props}></Icon>
