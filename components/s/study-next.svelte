<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csv-zmb0e.css';
import '../../css/j/j5ir4rbhy.css';
import '../../css/m/m2mxtz_ws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="csv-zmb0e"/><path class="j5ir4rbhy"/><path class="m2mxtz_ws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:study-next" {...props}></Icon>
