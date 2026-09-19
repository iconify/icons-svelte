<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sli08-0ex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sli08-0ex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:search-advanced" {...props}></Icon>
