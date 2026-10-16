<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtxjgl01m.css';
import '../../css/z/zy3xx9cdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rtxjgl01m"/><path class="zy3xx9cdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:water-butt-20" {...props}></Icon>
