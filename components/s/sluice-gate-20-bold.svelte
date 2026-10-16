<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f__3z1bhu.css';
import '../../css/g/grgea9bwv.css';
import '../../css/n/nroycebvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f__3z1bhu"/><path class="grgea9bwv"/><path class="nroycebvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sluice-gate-20-bold" {...props}></Icon>
