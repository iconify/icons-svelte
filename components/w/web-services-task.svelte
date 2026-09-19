<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkldj8bfo.css';
import '../../css/j/jiyjv684p.css';
import '../../css/t/tz_5mvbtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fkldj8bfo"/><path class="jiyjv684p"/><path class="tz_5mvbtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:web-services-task" {...props}></Icon>
