<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rab_xlb9n.css';
import '../../css/q/qv1h0pygk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rab_xlb9n"/><path class="qv1h0pygk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wattmeter-20-bold" {...props}></Icon>
