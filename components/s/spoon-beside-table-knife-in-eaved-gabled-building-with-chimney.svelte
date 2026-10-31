<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql5jfn30t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ql5jfn30t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:spoon-beside-table-knife-in-eaved-gabled-building-with-chimney" {...props}></Icon>
