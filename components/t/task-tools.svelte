<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogt714bjg.css';
import '../../css/t/trltflb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ogt714bjg"/><path class="trltflb5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:task-tools" {...props}></Icon>
