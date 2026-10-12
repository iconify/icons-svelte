<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt25qibgo.css';
import '../../css/e/e1d39acad.css';
import '../../css/t/tgryvbb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lt25qibgo"/><path class="e1d39acad"/><path class="tgryvbb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:stopwatch-20" {...props}></Icon>
