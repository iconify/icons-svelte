<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk4bfj7yl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kk4bfj7yl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:shuffle" {...props}></Icon>
