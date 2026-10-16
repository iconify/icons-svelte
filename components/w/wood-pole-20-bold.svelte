<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnwbcdcds.css';
import '../../css/r/rxia6zz2s.css';
import '../../css/p/pn4l7ibkh.css';
import '../../css/g/g21cvrbjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qnwbcdcds"/><path class="rxia6zz2s"/><path class="pn4l7ibkh"/><path class="g21cvrbjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wood-pole-20-bold" {...props}></Icon>
