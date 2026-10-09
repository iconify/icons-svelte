<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1c9zmbsp.css';
import '../../css/s/scp3oyb1s.css';
import '../../css/t/tp54fz-fo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f1c9zmbsp"/><path class="scp3oyb1s"/><path class="tp54fz-fo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermometer-up-20-bold" {...props}></Icon>
