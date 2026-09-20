<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrs8ykbjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="yrs8ykbjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:search" {...props}></Icon>
