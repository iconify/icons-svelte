<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olg41hbtg.css';
import '../../css/n/n795oxbwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="olg41hbtg"/><path class="n795oxbwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wine-bottle-20-bold" {...props}></Icon>
