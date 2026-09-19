<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezo0bkj3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ezo0bkj3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:youtube" {...props}></Icon>
