<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw2ccwbeu.css';
import '../../css/e/eyxhlubzl.css';
import '../../css/o/o25la7b3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xw2ccwbeu"/><path class="eyxhlubzl"/><path class="o25la7b3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wind-turbine-off-48" {...props}></Icon>
