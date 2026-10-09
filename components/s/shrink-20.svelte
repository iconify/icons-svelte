<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eiaeqebxr.css';
import '../../css/p/p8psecw5g.css';
import '../../css/e/eul6t1bqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="eiaeqebxr"/><path class="p8psecw5g"/><path class="eul6t1bqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shrink-20" {...props}></Icon>
