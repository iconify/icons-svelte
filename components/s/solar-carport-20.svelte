<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skan8zbga.css';
import '../../css/w/w879yqieg.css';
import '../../css/g/g5cv3vban.css';
import '../../css/u/uxaudcccd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="skan8zbga"/><path class="w879yqieg"/><path class="g5cv3vban"/><path class="uxaudcccd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-carport-20" {...props}></Icon>
