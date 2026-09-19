<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqz26c-5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="iqz26c-5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:virus-slash" {...props}></Icon>
