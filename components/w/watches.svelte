<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yj9yp3bwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yj9yp3bwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:watches" {...props}></Icon>
