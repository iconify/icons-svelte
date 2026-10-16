<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_3o7hbpq.css';
import '../../css/q/qfoc8pfkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t_3o7hbpq"/><path class="qfoc8pfkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tide-high-20-bold" {...props}></Icon>
