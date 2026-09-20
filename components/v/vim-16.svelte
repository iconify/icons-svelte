<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdk21pi7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bdk21pi7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:vim-16" {...props}></Icon>
