<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thq_bacgc.css';
import '../../css/n/njhh4kbbo.css';
import '../../css/z/za8ynewwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="thq_bacgc"/><path class="njhh4kbbo"/><path class="za8ynewwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:washer-20" {...props}></Icon>
