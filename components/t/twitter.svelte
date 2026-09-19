<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzbsxqb0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lzbsxqb0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:twitter" {...props}></Icon>
