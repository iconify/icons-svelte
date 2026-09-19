<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylugl128e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ylugl128e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:scissors" {...props}></Icon>
