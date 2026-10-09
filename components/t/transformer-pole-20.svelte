<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-9xc2bcj.css';
import '../../css/m/mxnl1347f.css';
import '../../css/g/g9pwdi6pr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s-9xc2bcj"/><path class="mxnl1347f"/><path class="g9pwdi6pr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:transformer-pole-20" {...props}></Icon>
