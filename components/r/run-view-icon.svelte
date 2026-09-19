<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oakl_4bkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oakl_4bkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:run-view-icon" {...props}></Icon>
