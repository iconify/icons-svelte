<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygn31xzau.css';
import '../../css/x/xw5_61bwy.css';
import '../../css/q/qgrtu-b6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ygn31xzau"/><path class="xw5_61bwy"/><path class="qgrtu-b6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:small-wind-turbine-48" {...props}></Icon>
