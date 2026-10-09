<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp_m7046n.css';
import '../../css/y/y2nhzjrjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tp_m7046n"/><path class="y2nhzjrjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:send-20" {...props}></Icon>
