<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2ejnib6s.css';
import '../../css/l/lmq15twty.css';
import '../../css/r/r2nbzfjyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h2ejnib6s"/><path class="lmq15twty"/><path class="r2nbzfjyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:small-wind-turbine-48-bold" {...props}></Icon>
