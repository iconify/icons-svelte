<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xuhs_mbfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xuhs_mbfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:suitcase" {...props}></Icon>
