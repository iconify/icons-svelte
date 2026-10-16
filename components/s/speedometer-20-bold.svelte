<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oorqf-8pe.css';
import '../../css/y/yvm9oub2m.css';
import '../../css/h/hvy9vrb1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oorqf-8pe"/><path class="yvm9oub2m"/><path class="hvy9vrb1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:speedometer-20-bold" {...props}></Icon>
