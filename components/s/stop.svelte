<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6bbd1bqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x6bbd1bqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:stop" {...props}></Icon>
