<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc25grbjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":488};
const content = `<path class="bc25grbjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:smugmug" {...props}></Icon>
