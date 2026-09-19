<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3p7ifb9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c3p7ifb9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:x-mark-16-solid" {...props}></Icon>
