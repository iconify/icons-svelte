<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5fem0brp.css';
import '../../css/m/mu5t7mbov.css';
import '../../css/x/xyen0l77b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k5fem0brp"/><path class="mu5t7mbov"/><path class="xyen0l77b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wind-turbine-off-20-bold" {...props}></Icon>
