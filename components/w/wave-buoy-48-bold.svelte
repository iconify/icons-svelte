<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhx9-1bok.css';
import '../../css/p/p47yd3vrn.css';
import '../../css/q/qjqywbfqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uhx9-1bok"/><path class="p47yd3vrn"/><path class="qjqywbfqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wave-buoy-48-bold" {...props}></Icon>
