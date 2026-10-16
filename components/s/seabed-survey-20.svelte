<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7o4albhq.css';
import '../../css/z/z70t_abxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z7o4albhq"/><path class="z70t_abxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:seabed-survey-20" {...props}></Icon>
