<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flvfhbxkj.css';
import '../../css/e/epd7hgbik.css';
import '../../css/i/iw_3o3g9q.css';
import '../../css/d/dq1tynbis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="flvfhbxkj"/><path class="epd7hgbik"/><path class="iw_3o3g9q"/><path class="dq1tynbis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:small-wind-turbine-20-bold" {...props}></Icon>
