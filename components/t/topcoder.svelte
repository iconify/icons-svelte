<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncjstd5lp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ncjstd5lp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:topcoder" {...props}></Icon>
