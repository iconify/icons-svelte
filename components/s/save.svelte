<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkr_h4dal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lkr_h4dal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:save" {...props}></Icon>
