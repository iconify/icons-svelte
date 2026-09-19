<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkmdx5b_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bkmdx5b_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:swords" {...props}></Icon>
