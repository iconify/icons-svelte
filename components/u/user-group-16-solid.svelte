<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohga79bvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ohga79bvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:user-group-16-solid" {...props}></Icon>
