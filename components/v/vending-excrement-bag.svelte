<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuwwfibnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uuwwfibnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:vending-excrement-bag" {...props}></Icon>
