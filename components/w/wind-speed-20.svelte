<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trmttkbvo.css';
import '../../css/h/hire59f7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="trmttkbvo"/><path class="hire59f7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wind-speed-20" {...props}></Icon>
