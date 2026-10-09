<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov7zehb3m.css';
import '../../css/r/rs63jfdfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ov7zehb3m"/><path class="rs63jfdfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:saw-20" {...props}></Icon>
