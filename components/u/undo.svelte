<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvm4kcb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tvm4kcb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:undo" {...props}></Icon>
