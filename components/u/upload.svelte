<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow1wj2bms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ow1wj2bms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:upload" {...props}></Icon>
