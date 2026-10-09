<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycu-hhf9w.css';
import '../../css/g/g3yqyfbnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ycu-hhf9w"/><path class="g3yqyfbnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sofa-20" {...props}></Icon>
