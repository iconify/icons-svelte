<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-dt4mq6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e-dt4mq6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:virus-covid" {...props}></Icon>
